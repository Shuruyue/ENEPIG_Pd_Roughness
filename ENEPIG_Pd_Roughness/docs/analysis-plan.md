## Pd Layer Roughness Analysis Plan (ENEPIG)

This document outlines the sequential experiments and their intended purposes to determine the dominant factors influencing surface roughness of Pd layers in ENEPIG finishes.

---

### Core Research Question

**Why does the surface roughness of Pd increase with layer thickness?**

---

### Analysis Sequence and Purpose

| Step | Analysis Target             | Objective                                  | Method/Tool           | Expected Outcome                         |
|------|-----------------------------|--------------------------------------------|------------------------|------------------------------------------|
| 1    | SEM image sorting           | Confirm correlation between thickness and visual roughness | SEM (cross-section)   | Establish base observation                |
| 2    | Bare Ni(P) surface check    | Rule out Ni(P) roughness inheritance       | SEM, AFM               | Determine if Pd replicates Ni surface     |
| 3    | Surface roughness quantification | Measure Ra, Rq, Rz on each Pd sample   | AFM (tapping mode)     | Get numerical roughness trend             |
| 4    | Thickness vs Roughness Plot | Visualize growth-induced roughness         | Python / Plotting      | Identify linear or non-linear behavior    |
| 5    | Literature extraction: plating chemistry | Identify role of reductant (N₂H₄ vs H₂PO₂⁻) | Literature + SDS | Link bath chemistry to growth trend       |
| 6    | Residual stress analysis    | Evaluate strain as roughness driver        | XRD (2θ scan)          | Detect peak shifts / broadening           |
| 7    | Crystallographic orientation mapping | Check for grain coarsening or texture shift | EBSD (FIB-prepared) | See if roughness correlates to orientation evolution |
| 8    | Correlation map & hypothesis update | Classify major vs minor contributing factors | Cross-analysis    | Select final mechanism candidates         |

---

### Supporting Questions to Answer

- Is the roughness purely geometric or related to crystalline stress?
- Is there a critical thickness where roughening accelerates?
- Does the plating bath chemistry affect nucleation mode?

---

### Outputs to Prepare

- AFM roughness plots
- SEM annotated sections
- XRD peak comparison
- EBSD inverse pole figure (IPF) maps
