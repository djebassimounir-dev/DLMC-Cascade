# DLMC-SPARC Analysis

This repository contains computational notebooks and scripts for the **DLMC (Dynamic Local Mass Clustering) analysis** of SPARC galaxy rotation curves.  
Using the **FluxCore v5 framework**, it models unified dark matter dynamics and validates rotational velocity profiles against SPARC data.  

The framework integrates **baryonic contributions, radial acceleration relations (RAR), and gravitational lensing effects**, providing a reproducible and modular tool for astrophysical research in modified gravity and galactic dynamics.

---

## DOI
- **FluxCore v5**: [10.5281/zenodo.18843446](https://doi.org/10.5281/zenodo.18843446)  
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18843446.svg)](https://doi.org/10.5281/zenodo.18843446)
- **DLMC-SPARC Analysis**: [10.5281/zenodo.18907865](https://doi.org/10.5281/zenodo.18907865)  
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18907865.svg)](https://doi.org/10.5281/zenodo.18907865)
- **DLMC Framework: Perturbative Analysis of Galactic Gravitational Flux**: [10.5281/zenodo.18997307](https://doi.org/10.5281/zenodo.18997307)  
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18997307.svg)](https://doi.org/10.5281/zenodo.18997307)

---

## Files
This repository now includes the full DLMC Framework for perturbative galactic gravitational flux analysis:

- `dlmc-fram.ipynb` — Jupyter notebook with step-by-step simulations
- `dlmc-fram.py.py` — Python scripts for numerical integration and visualization
- `dlmc-fram.pdf` — PDF version of the report
- `dlmc-fran-html.html` — HTML version of the report
- `readme.txt` — Quick usage guide
- Figures (`output_*.png`) — Simulation results

---

## Instructions
1. Open the notebook `dlmc-fram.ipynb` for step-by-step simulations.  
2. Install required Python packages:
   ```bash
   pip install numpy pandas matplotlib
