## RNA-Chip Hybridized Association Mapping Platform (RNA-CHAMP)

This repo stores dataset and code used in the manuscript:

### Massively Parallel Profiling of RNA-targeting CRISPR-Cas13d
Hung-Che Kuo, Joshua Prupes,  Chia-Wei Chou,  Ilya J. Finkelstein
doi: https://doi.org/10.1101/2023.03.27.534188

### Image analysis pipeline
RNA-CHAMP is a protein-RNA interaction profiling platform based on a previously described CHAMP.
Image align pipeline is identical to CHAMP and available at https://github.com/finkelsteinlab/CHAMP.

Fitted data use in the manuscript is available in the cas13d_binding_data directory.
Linear model and machine learning model is available in the cas13d_modeling directory.

### target # explaination
Target 1 & 2 were used in the PFS library. All PFS library has three randomized nucleotides on both ends of the target.
Target 1 & 3 were used to generate partailly matched library (mismatches, insertions, and deletions).
