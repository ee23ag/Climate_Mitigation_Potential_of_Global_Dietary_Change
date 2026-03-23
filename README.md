# Climate Mitigation Potential of Global Dietary Change

This repository contains the data and code used to analyse the impact of global dietary transitions on greenhouse gas emissions and projected global temperature change using the Finite Amplitude Impulse Response (FaIR) simple climate model (SCM) version 1.6.4.

This work supports the dissertation:

“The Climate Mitigation Potential of Global Dietary Change: Projected Global Temperature Implications Using the FaIR Model”

---

## Repository Structure

### `data/`
Contains all input datasets used in the analysis, including:
- CO₂, CH₄, N₂O emissions for each dietary scenario (business-as-usual, moderate, progressive, reduced-meat, low-emission and plant-based)
- Differences between each scenario and the business-as-usual (BAU) pathway
- UN population projections
- Emissions uncertainty ranges
- Indicators of global climate change

### `notebook/`
Contains the Jupyter notebook used to generate all figures and results presented in the dissertation.

---

## Methods Overview

Dietary emissions scenarios were constructed and compared against a BAU baseline. Emissions were input into the FaIR SCM (v1.6.4) to simulate changes in global mean surface temperature (GMST).

The FaIR model was implemented following official documentation:
https://docs.fairmodel.net/en/v1.6.4_a/intro.html

---

## Reproducibility

To reproduce the results:

1. Clone the repository  
2. Open the notebook in the `notebook/` directory  
3. Run all cells to regenerate figures and outputs  

---

## Notes

- All figures in the dissertation are generated directly from the code provided.
- File paths are structured to ensure reproducibility using relative directories.

---

## Author

Abigael Graham
