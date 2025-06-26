# Drug Similarity Search using RDKit and ChEMBL

This project performs drug similarity analysis using molecular fingerprints and Tanimoto similarity, leveraging the RDKit and ChEMBL databases. It identifies molecules in a dataset that are structurally similar to known reference drugs.

## Overview

The script:

1. Loads SMILES strings from a CSV file.
2. Computes Morgan fingerprints (circular fingerprints) using RDKit.
3. Calculates Tanimoto similarity scores between each compound and reference drugs.
4. Ranks molecules based on average similarity scores.
5. Queries ChEMBL for similar molecules to the reference drugs.
6. Saves sorted results and ChEMBL hits as CSV files.
7. Visualizes similarity score distributions and correlations.

## Dependencies

Install the required packages via pip:

```bash
pip install rdkit-pypi chembl_webresource_client pandas matplotlib seaborn
```

## Input

- A CSV file containing a column named `smiles` with SMILES representations of molecules.
- Example input file path (as used in the notebook):  
  `/content/drive/MyDrive/drug_information.csv`

## Reference Drugs

The following reference molecules are used:

- Everolimus
- Aspirin
- Troglitazone

## Output

- `sorted_molecules2.csv`: List of dataset molecules ranked by average similarity to the references.
- `chembl_similar_molecules2.csv`: Molecules from ChEMBL with at least 70% similarity to each reference.

## Visualizations

- Histogram of average similarity scores.
- Heatmap showing correlation between similarity scores for each reference drug.
- Listing of molecules with high similarity (> 0.8) to any reference.

## Usage

Run the notebook step-by-step. Make sure the input file path is valid and accessible.

## Notes

- The notebook uses Tanimoto similarity on Morgan fingerprints (radius = 2).
- Missing or invalid SMILES are handled gracefully and ignored in similarity calculations.

## Author

This analysis is part of the TFM (Final Master's Thesis) project of Nathan Junod.
