# 🧠 Morphological Segmentation with Morfessor for Telugu

This project is part of the **INFO-539** course and aims to create an accessible technical tutorial for **unsupervised morphological segmentation** using **Morfessor**, applied to **Telugu**—a morphologically rich and low-resource language.

---

## 🔍 Objective

- Train a Morfessor model on Telugu text data
- Perform unsupervised morphological segmentation
- Evaluate segmentation quality
- Provide a tutorial with code, explanations, and visual examples

---
```
## 📂 Repository Structure
morfessor-telugu-tutorial/
│
├── data/ # Raw and processed Telugu text datasets
│ ├── telugu_500.txt
│ ├── telugu_10000.txt
│ ├── mixed_telugu_2000.txt
│ └── Tested500words.txt
│
├── results/ # Segmentation output files
│ └── segmented_output_500_from_2000mix.txt
│
├── notebooks/ # Jupyter Notebooks
│ └── morfessor_tutorial.ipynb
│
├── environment.yml # Conda environment setup file
├── proposal.md # Initial project proposal
└── README.md # Project overview

```

## ⚙️ Installation

To run this tutorial on your own system:

```bash
git clone https://github.com/Giridharkotha/morfessor-telugu-tutorial.git
cd morfessor-telugu-tutorial
conda env create -f environment.yml
conda activate morfessor-env

