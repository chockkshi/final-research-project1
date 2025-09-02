
# Modelling glycine in Cardiac Mitochondria using Flux Balance Analysis
# 🧬 Cardiac Mitochondrial Model Analysis

This repository contains the analysis of a universal mitochondrial model, customized for mouse cardiac tissue, using constraint-based modeling and flux balance analysis (FBA).

---

## 📂 Repository Contents
- `analysis_notebook.ipynb`: Main Jupyter Notebook containing full code and analysis.
- `4_universal_mito_model.xml`: SBML model file.
- `Heart_data.tsv`: Omics data specific to heart tissue.
- `efflux_method.py`: Custom Python method for applying gene expression constraints (Eflux method).
- `reaction.csv`: CSV file cataloging all reactions extracted from the model.
- `mouse_cardiac_fluxes.svg`: Plot showing predicted import and secretion fluxes.
  
---

## Installation

To get started with the Jupyter notebooks and simulation tools, you will need to set up a Python environment with the necessary dependencies. We recommend using **conda** or **pip** for installation.

### Using Conda

```bash
conda create --name mitomammal python=3.8
conda activate mitomammal
conda install jupyter numpy pandas matplotlib cobra
```

### Using Pip

```bash
pip install jupyter numpy pandas matplotlib cobra
```

---

## Usage

Once the environment is set up, you can start Jupyter Notebook by running:

```bash
jupyter notebook
```

This will open a local server where you can explore the available notebooks in this repository.

---


This will open a local server where you can explore the available notebooks in this repository.
## 🚀 Project Summary
- **Load** mitochondrial metabolic model.
- **Catalog** all reactions.
- **Integrate** heart tissue omics data.
- **Constrain** the model using the Eflux method.
- **Optimize** for ATP production using Flux Balance Analysis.
- **Analyze** uptake and secretion patterns.


---

## 🔗 Repository Link
[Click here to access the GitHub repository](https://github.com/chockkshi/final-research-project1)

---




