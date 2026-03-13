# Hidden Force: Universal Scaling Law in Nonlinear Dissipative Fields
# Author: Mounir Djebassi (Independent Researcher)
# ORCID: 0009-0009-6871-7693
# Date: March 2026
# DOI: 10.5281/zenodo.18985830

========================================================================
1. PROJECT OVERVIEW
========================================================================
This repository contains the full numerical framework and reproducibility 
notebooks for the discovery of the Universal Scaling Law: 
std(φ) ∝ α^(-1/2) 

The study investigates a novel class of nonlinear dissipative scalar 
fields where dissipation is governed by the "Hidden Force" term: 
-k * ρ * |∇φ|^α.

Key discovery: The field fluctuations (standard deviation) follow a 
precise power law with an exponent β ≈ -0.5, independent of diffusion (D), 
relaxation time (τ), or coupling strength (k).

========================================================================
2. REPRODUCIBILITY GUIDE
========================================================================
To reproduce the results presented in the Physical Review E submission:
1. Open the Jupyter Notebook: "Hidden_Force_Scaling_Analysis.ipynb"
2. Select "Kernel" -> "Restart & Run All".
3. Execution time: ~5-10 minutes (depending on CPU) for 1,200 simulations.

The code is optimized for numerical stability using:
- Epsilon-safety (1e-10) for gradient norms.
- Explicit Euler scheme with stability clipping.
- Automated log-log regression for exponent extraction.

========================================================================
3. FILE STRUCTURE
========================================================================
- /Notebooks: Main simulation and analysis (.ipynb)
- /Figures: High-resolution scaling plots and PDFs (.png, .pdf)
- /Scripts: Standalone Python functions for the Hidden Force model (.py)
- /Data: Aggregated robustness meta-analysis results (.csv)

========================================================================
4. TECHNICAL SUMMARY
========================================================================
- Measured Exponent: β = -0.5002 ± 0.0003
- Correlation: R² = 0.9987
- Validated Regimes: α ∈ [0.1, 10]
- Dimensions: 2D and 3D (Lattice 50x50 / 30x30x30)

========================================================================
5. CITATION & LICENSE
========================================================================
If you use this framework or the Hidden Force model in your research, 
please cite:
Djebassi, M. (2026). Hidden Force: Universal Scaling Law in a Nonlinear 
Dissipative Scalar Field. Zenodo. DOI: 10.5281/zenodo.18985830

License: Creative Commons Attribution 4.0 International (CC-BY-4.0).
========================================================================