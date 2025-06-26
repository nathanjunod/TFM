# ADGRE2 Pathway Map Visualization

This notebook creates a visual diagram representing known and proposed modulatory pathways affecting **ADGRE2** expression. It integrates interactions involving inflammation, transcriptional regulators, kinase signaling, and drug influences.

## Objective

To map out key biological pathways and drugs that may influence **ADGRE2** expression, particularly in the context of inflammation and translational regulation.

## Features

- Constructs a directed graph using the **Graphviz** library.
- Includes pathway nodes for:
  - PPAR-γ
  - NF-κB
  - COX inhibition
  - JAK/STAT
  - Phosphorylation
  - mTOR
  - FKBP-12
  - ADGRE2 expression
- Annotates drugs that modulate each pathway.
- Highlights speculative or literature-supported links using edge styles (e.g. dashed, dotted).

## Drug Classes

- **PPAR-γ Activators**: Pioglitazone, Rosiglitazone, Troglitazone
- **COX Inhibitors**: Salsalate, Benorilate
- **JAK/STAT Modulators**: Nitazoxanide, Diacerein
- **mTOR Inhibitors**: Everolimus, Sirolimus, Temsirolimus
- **Miscellaneous**: Pemetrexed, Acetomenaphthone, Salicylic Acid
- **Special Note**: Aspirin (marked as possibly aggravating vascular ulcers)

## Requirements

Install necessary dependencies:

```bash
pip install graphviz
```

> You must have [Graphviz installed](https://graphviz.org/download/) on your system for rendering.

## Output

- A visual diagram: `ADGRE2_Pathway_Diagram.png`
- Source DOT code for transparency and reproducibility.

## Diagram Features

- **Color coding**: Emphasizes key pathways (e.g., inflammation in ellipse, ADGRE2 in red).
- **Shapes**: Boxes for pathways, notes for drugs.
- **Directional edges**: Represent modulation (e.g., inhibition, activation).
- **Dashed/Dotted edges**: Indicate speculative or weaker evidence.

## Use Case

Ideal for researchers and students exploring:

- Pathway-targeted drug repurposing.
- Mechanistic hypotheses for ADGRE2 regulation.
- Visual summaries for presentations or publications.

## Author

Nathan Junod
