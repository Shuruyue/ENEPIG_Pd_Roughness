# Data Directory (Public Version)

This folder is intended to organize and document the types of raw data used in the ENEPIG Pd Roughness study.  
However, due to confidentiality and intellectual property restrictions, **no actual analysis data is published here**.

## Confidentiality Notice

The raw SEM, AFM, XRD, and EBSD files generated from experimental observations are stored in a separate _private repository_:  
**ENEPIG_Pd_Roughness_Internal**

This public repository may includes structural placeholders (via `.keep` files) to illustrate the directory layout.

If you are a collaborator or reviewer who needs access to the full dataset, please contact the project owner with the following:

- Your full name and affiliation  
- Purpose of data access  
- Preferred method for secure file sharing

_Contact_: **zhongyue364@gmail.com**  
_Project Maintainer_: **[@shuruyue](https://github.com/shuruyue)**

---

## Intended Structure

The full `data/` directory (in the private repo) includes:

```plaintext
data/
├── SEM/         ← SEM images: cross-sections and surface morphology
├── AFM/         ← AFM surface roughness scans (height data)
├── XRD/         ← X-ray diffraction peaks and FWHM analysis files
├── EBSD/        ← Grain orientation and size data from EBSD scans
└── Vendor/      ← Original technical sheets and SDS from suppliers
