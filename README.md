# Dataset: Intelligent Control of Synthetic Probiotics and AMPs

This directory contains the raw experimental data and genetic sequences used in our study, **"Intelligent Control of Synthetic Probiotics and AMPs in Simulated Wound Ecosystems"**.

## 📂 Data Overview

The experimental data is provided in **Excel (.xlsx)** format. The files correspond to the results presented in **Figures 1–3** of the manuscript:

### Figure 1: Protein Secretion & Hydrogel Validation
Data validating hGM-CSF secretion by engineered *E. coli* and its release kinetics from chitosan hydrogels.
* **`cell proliferation.xlsx`**: 293T cell proliferation assay comparing conditioned medium from different strains (Control, PelB, pKJE7).
* **`hydrogel diffusion.xlsx`**: Time-dependent protein release kinetics measured by Nanodrop.
* **`ELISA diffusion test.xlsx`**: Quantification of hGM-CSF release using ELISA.

### Figure 2: Bacterial Growth Kinetics
Growth dynamics of pathogenic *E. coli* and probiotic *L. lactis* for ODE model fitting.
* **`E. coli growth curve OD.xlsx`**: Optical density (OD600) measurements for *E. coli*.
* **`E. coli growth curve CFU.xlsx`**: Colony Forming Units (CFU) counts for *E. coli*.
* **`L. lactis growth curve OD.xlsx`**: Standard growth curve (OD600) for *L. lactis*.
* **`L. lactis growth curve CFU.xlsx`**: Standard growth curve (CFU) for *L. lactis*.
* **`L. lactis growth curve in 37C O.xlsx`**: Temperature stress test at 37°C (OD600).
* **`L. lactis growth curve in 37C C.xlsx`**: Temperature stress test at 37°C (CFU).

### Figure 3: AMP Efficacy & Resistance
Dose-response and resistance evolution assays using hBD-3 (AMP).
* **`AMP to L. lactis pretest.xlsx`**: Probiotic tolerance test under varying AMP concentrations.
* **`AMP to E. coli.xlsx`**: *E. coli* survival rates and killing efficiency.
* **`AMP to E. coli second dose.xlsx`**: Adaptive resistance test (second-dose challenge).

### Other
* **`antibiotic selection.xlsx`**: Preliminary antibiotic marker selection data.

---

## 🧬 Genetic Sequences
We provide the plasmid maps and sequences used for strain construction (compatible with **SnapGene Viewer**):

* **`PelB-rhGM-CSF.dna`**: Full construct containing the PelB signal peptide fused to the hGM-CSF coding region.
* **`rhGM-CSF.dna`**: Coding sequence for the human Granulocyte-Macrophage Colony-Stimulating Factor.

---

## 🔗 Citation
If you utilize this dataset or the sequences, please cite:
> Ciou, Z.-C., Huang, P.-C., et al. "Intelligent Control of Synthetic Probiotics and AMPs in Simulated Wound Ecosystems." *Computers in Biology and Medicine* (Submitting).
