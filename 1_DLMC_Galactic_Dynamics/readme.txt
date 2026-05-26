# DLMC Perturbative Analysis - Galactic Rotation Curves (SPARC)
**Mounir Djebassi** | **ORCID:** 0009-0009-6871-7693  
**Affiliation:** Independent Research Association (Bucharest)

## Project Overview
This repository contains the numerical implementation of the **Dark Low-Mass Component (DLMC)** framework. It provides a perturbative analysis of the scalar field $\phi$ to explain galactic rotation curves without the need for traditional dark matter halos or MOND-specific modifications.

This work specifically validates the model against **SPARC** (Spitzer Photometry and Accurate Rotation Curves) datasets, achieving a reduced $\chi^2$ close to 1.0.

## Files in this Repository
- `bio-astro.ipynb`: The core Jupyter Notebook containing the full simulation, perturbative expansion, and $\chi^2$ optimization.
- `requirements.txt`: List of Python libraries required to run the simulation.
- `README.md`: Project documentation and metadata.

## How to Run
1. Ensure you have **Python 3.8+** and **JupyterLab** installed.
2. Install dependencies: `pip install -r requirements.txt`.
3. Open `bio-astro.ipynb` and run all cells to reproduce the results and visualizations.

## Key Features
- **Perturbative Framework**: Implementation of $\phi_0$ (leading order) and $\epsilon_1 \phi_1, \epsilon_2 \phi_2$ (higher-order corrections).
- **Physical Integration**: Exact radial integration for enclosed mass calculations.
- **Statistical Fitting**: Automated $\chi^2$ landscape analysis for parameter optimization.

## License
This project is released under the **MIT License**.

## Citation
If you use this work in your research, please cite:
*Djebassi, M. (2026). Perturbative DLMC Analysis: Higher-Order Scalar Field Corrections and Chi-Square Validation in SPARC Galaxies. Zenodo.*
