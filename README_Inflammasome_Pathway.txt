# Inflammasome Activation Pathway Diagram

This notebook generates a high-resolution molecular pathway diagram illustrating the two-signal activation model of the **NLRP3 inflammasome**, with a special focus on the upstream influence of the **ADGRE2 (EMR2)** receptor and its interaction with chondroitin sulfate B (CS-B).

## Biological Context

The figure outlines:

- **Signal 1 (Priming)**: Triggered by Toll-like receptors (TLRs), leading to **NF-κB** activation and transcription of inflammasome precursors (pro-IL-1β, pro-IL-18, pro-caspase-1).
- **Signal 2 (Activation)**: Triggered by ADGRE2 (EMR2) binding to CS-B, initiating signaling cascades involving Gα16, PLC-β, PI3K, Ca²⁺ flux, ROS, and K⁺ efflux that converge to activate the **NLRP3 inflammasome**.
- **Final Output**: Maturation and release of inflammatory cytokines **IL-1β** and **IL-18**.

## Technical Overview

- Built using the **Graphviz** Python library.
- Exports a high-resolution PNG (`ADGRE2_Inflammasome_Pathway.png`).
- Layout is left-to-right (LR), with enhanced DPI and large font sizes for clarity in Word documents and presentations.

## Requirements

To run the notebook, install the required package:

```bash
pip install graphviz
```

Also ensure **Graphviz** is installed on your system from:  
https://graphviz.org/download

## Output

- A clean, labeled figure exported as:
  - `ADGRE2_Inflammasome_Pathway.png`
- Optional: view the DOT source for further customization.

## Use Case

This figure is designed for:

- Inclusion in theses, reviews, and scientific presentations.
- Visualizing the two-signal model of inflammasome activation with ADGRE2-specific context.
- Highlighting drug or molecular intervention points in inflammation pathways.

##Author

Nathan Junod