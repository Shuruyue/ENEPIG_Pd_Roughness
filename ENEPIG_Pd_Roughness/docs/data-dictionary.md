# Data Dictionary  

This document defines and explains the key variables used in the **ENEPIG Pd roughness project**. It ensures consistent terminology across data acquisition, processing, and reporting.

| **Variable Name**   | **Description**                                                                                                                                   | **Unit**       |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| `Sample_ID`         | **Unique identifier** for each sample. Encodes plating condition and target thickness.                                                           | –              |
| `Pd_Thickness`      | **Palladium layer thickness**, measured via SEM cross-section. Calibrated based on image scale; corresponds to vertical Pd height.              | nm             |
| `Ra`                | **Arithmetic average roughness** from AFM scan: average deviation from mean surface height. <br>**Ra = (1/N) ∑\|Zᵢ\|**                           | µm             |
| `Rq`                | **Root mean square roughness**: standard deviation of surface height values. <br>**Rq = √[(1/N) ∑Zᵢ²]**                                           | µm             |
| `Rz`                | **Mean peak-valley height**: average vertical distance between top 5 peaks and bottom 5 valleys in a line scan.                                  | µm             |
| `SEM_Magnification` | SEM image **magnification level**. Affects observable detail and measurement precision.                                                          | ×              |
| `Observed_IMC`      | Intermetallic compounds detected at interfaces, based on SEM/EDS or elemental mapping.                                                       | qualitative    |
| `Date_Collected`    | Date of data acquisition, used to track progress and experimental conditions.                                                                | **YYYY-MM-DD**     |
| `AFM_Mode`          | AFM operating mode (e.g., tapping, contact), affecting scan fidelity and image contrast.                                                     | text           |
| `AFM_Scan_Size`     | Lateral scan area in AFM measurements. Important for comparing surface metrics across samples.                                               | µm × µm        |
| `XRD_Peak_Pos`      | **Position of Pd diffraction peaks** (2θ), indicating strain or lattice shifts.                                                                  | degrees (°)    |
| `XRD_FWHM`          | **Full width at half maximum** of XRD peaks. Used in **Scherrer equation** to estimate grain size.                                               | degrees (°)    |
| `EBSD_Grain_Size`   | **Average grain size** derived from EBSD mapping, using misorientation segmentation.                                                             | µm             |
| `EBSD_Texture`      | **Dominant crystallographic orientation** from EBSD inverse pole figure (IPF). Provides insights into preferred grain growth direction.         | text           |
