# Bioinformatics & Clinical Data Analysis Portfolio
**Marián de Juan Carnero** | PharmD, MSc Bioinformatics & Dermopharmacy 

Welcome to my portfolio. This repository showcases my transition from clinical pharmacy to bioinformatics, focusing on high-dimensional biological data integration, multivariate statistics, and molecular pharmacology.

## 🧬 Core Projects

### 1. Multi-Omic Data Integration (Transcriptomics & Metagenomics)
**Context:** Research conducted at IHSM La Mayora (CSIC-UMA).
**Objective:** Identify highly correlated multi-omic biomarkers under stress conditions.
**Tools:** `R`, `mixOmics`, `tidyverse`, `ggplot2`.
**Highlights:**
* Implementation of the DIABLO framework (`block.splsda`) to integrate transcriptomic (`counts_matrix`) and metagenomic (`genus_abund`) datasets.
* **Methodological note:** During algorithm tuning (perf/tune functions), I explicitly disabled parallel computing to ensure mathematical stability, total reproducibility, and strict control over the cross-validation folds.

### 2. QSPR Modeling & Molecular Docking of PDE-4 Inhibitors
**Context:** Master's Thesis (TFM) in Bioinformatics.
**Objective:** Evaluate the pharmacokinetic properties and binding affinities of Apremilast and Roflumilast.
**Tools:** `Python`, `AutoDock Vina`, `PyRx`, `RDKit`, `SwissADME`.
**Highlights:**
* In silico ADMET evaluation and docking simulations to predict ligand-receptor interactions at the molecular level.

## 💻 Tech Stack
* **Languages:** R, Python, SQL/MySQL
* **Data Science & ML:** mixOmics, Biopython, Pandas, PyTorch, TensorFlow
* **Clinical Knowledge:** Pharmacological pathways, traceability, regulatory compliance, molecular biology.
