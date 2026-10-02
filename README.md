# Lyn activation-loop MSM data

Computational supporting data for the manuscript **“Ligand-Based Design of Lyn-Selective Type II Kinase Inhibitors by Rational Tail Modification of Imatinib.”**

## Contents

- `16_Lyn_CA_CB_CD_CE_T1_1us.xvg` through `T5`: five GROMACS distance-feature trajectories for Lyn bound to compound 16 (m-Cl), one per independent replicate.
- `22_Lyn_CA_CB_CD_CE_T1_1us.xvg` through `T5`: five corresponding trajectories for Lyn bound to compound 22 (o-Cl).
- `Lyn_Compound_16_complex.pdb` and `Lyn_Compound_22_complex.pdb`: the two supplied Lyn–compound starting complexes.

Each `.xvg` file has a time column in picoseconds followed by four distance columns in nanometers. The four features describe Tyr397-centered Cα–Cα distances used for the activation-loop analysis. The retained trajectories run from 25,000 to 1,025,000 ps at 10 ps intervals. The original GROMACS metadata headers are preserved.

The manuscript describes the modeling protocol and identifies the residues used for the four distance features. Analysis scripts and the full molecular-dynamics trajectories are not included in this repository.
