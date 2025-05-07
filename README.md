# Morphological Segmentation with Morfessor for Telugu

This project is part of the INFO-539 course and aims to create an accessible technical tutorial for unsupervised morphological segmentation using **Morfessor**, applied to **Telugu**, a morphologically rich and low-resource language.

## 🔍 Objective

To train and evaluate a Morfessor model on Telugu text data and produce a hands-on, annotated tutorial demonstrating its practical usage and segmentation quality.

## 📁 Contents

- `morfessor_tutorial.ipynb`: Jupyter notebook tutorial with code + explanations
- `data/`: Raw and (manually) annotated Telugu data for training and evaluation
- `results/`: Output segmentations and evaluation results
- `environment.yml`: Conda environment file with dependencies

## ⚙️ Installation

To run this tutorial on your own system:

```bash
git clone https://github.com/Giridharkotha/morfessor-telugu-tutorial.git
cd morfessor-telugu-tutorial
conda env create -f environment.yml
conda activate morfessor-env

