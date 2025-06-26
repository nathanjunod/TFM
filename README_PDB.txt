# PDB Comparison Script for ADGRE2 AlphaFold Models

This project provides a Google Colab-compatible script that compares multiple AlphaFold-predicted PDB models of the human ADGRE2 protein using structural alignment and RMSD calculations.

## 🧬 Purpose

ADGRE2 (EMR2) is an adhesion GPCR implicated in inflammatory signaling and diseases such as vibratory urticaria. This script quantitatively compares predicted 3D structures of ADGRE2 to assess structural variability across AlphaFold models.

## 🛠️ Features

- Parses multiple `.pdb` structure files using **Biopython**
- Performs structural superimposition using backbone atoms
- Computes **pairwise RMSD** (Root Mean Square Deviation)
- Outputs a Pandas DataFrame of the RMSD matrix

## 💻 Requirements

- Python 3 (recommended in Google Colab)
- `biopython`
- `pandas`
- `.pdb` structure files from AlphaFold (placed in Google Drive)

## 🚀 How to Use

1. Mount your Google Drive in Colab
2. Update the `model_files` list with paths to your PDB files
3. Run the notebook cells
4. View the RMSD matrix for structural differences

## 📂 Files

- `PDB_Comparison_Script.ipynb`: Main notebook for RMSD analysis
- `README_PDB.txt`: This documentation

---

Author: Nathan Junod