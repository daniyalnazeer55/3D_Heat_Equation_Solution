# 1D Heat Equation Solver and 3D Visualizer

This project provides a Python implementation for solving and visualizing the 1D heat equation using analytical series solutions combined with numerical integration (`scipy.integrate.quad`) and 3D surface plotting (`matplotlib`).

## Features
- **Numerical Integration**: Computes Fourier coefficients dynamically for a given initial condition $f(x)$ using `scipy.integrate.quad`.
- **Analytical-Numerical Hybrid**: Evaluates the temperature distribution $u(x, t)$ over position and time.
- **3D Surface Plotting**: Generates an interactive/static 3D surface plot displaying position vs. time vs. temperature using Matplotlib's 3D projection.

## Prerequisites & Installation

Make sure you have Python 3.7+ installed. Clone this repository and install the required dependencies using `pip`:

```bash
pip install -r requirements.txt

Usage: Launch Jupyter Notebook or Jupyter Lab: Bash jupyter notebook
Open the .ipynb file. Modify parameters such as thermal diffusivity (alpha), length (L), or the initial condition function (f(x))
in the configuration cells to explore different physical behaviors.
Run all cells to render the 3D surface plot.
