final-research-project/
│
├── README.md              # ➔ project description and instructions
├── 4_universal_mito_model.xml   # ➔ your model file (upload this!)
├── Heart_data.tsv          # ➔ your heart-specific data (upload this!)
├── efflux_method.py        # ➔ your custom Eflux function file (upload this!)
├── analysis_notebook.ipynb # ➔ your full Jupyter Notebook (the code you gave)
├── reactiondummy.csv       # ➔ CSV file you generate from reactions
├── mouse_cardiac_fluxes.svg # ➔ the saved figure
└── (maybe create /plots, /data folders later)

# 🧬 Cardiac Mitochondrial Model Analysis

This repository contains the analysis of a universal mitochondrial model, customized for mouse cardiac tissue, using constraint-based modeling and flux balance analysis (FBA).

---

## 📂 Repository Contents
- `analysis_notebook.ipynb`: Main Jupyter Notebook containing full code and analysis.
- `4_universal_mito_model.xml`: SBML model file.
- `Heart_data.tsv`: Omics data specific to heart tissue.
- `efflux_method.py`: Custom Python method for applying gene expression constraints (Eflux method).
- `reactiondummy.csv`: CSV file cataloging all reactions extracted from the model.
- `mouse_cardiac_fluxes.svg`: Plot showing predicted import and secretion fluxes.
  
---

## 🚀 Project Summary
- **Load** mitochondrial metabolic model.
- **Catalog** all reactions.
- **Integrate** heart tissue omics data.
- **Constrain** the model using the Eflux method.
- **Optimize** for ATP production using Flux Balance Analysis.
- **Analyze** uptake and secretion patterns.
- **Explore** how glycine import affects ATP production.

---

## 🛠️ Future Work
- Compare heart-specific fluxes with other tissues (liver, muscle).
- Introduce additional omics constraints (proteomics, metabolomics).
- Test alternative objective functions (biomass production, minimal NADH usage).
- Visualization improvements (flux maps, pathway-specific fluxes).

---

## 🔗 Repository Link
[Click here to access the GitHub repository](https://github.com/chockkshi/final-research-project1)

---

## 📱 QR Code to this Repository
![QR Code](qr-code.png)

_(Scan the code to directly access the repo!)_

---

## 📜 How to Run
#1. Clone the repo:
