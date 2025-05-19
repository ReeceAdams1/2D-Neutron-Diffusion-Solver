# 2D-Neutron-Diffusion-Solver
# 2D Diffusion Solver and Comparison to 1D Diffusion

This repository contains a Jupyter Notebook implementation of a **2D neutron diffusion solver** and a comparison to a **1D analytical approximation** using transverse buckling. The project models fixed boundary conditions in both dimensions and demonstrates numerical techniques for solving diffusion problems using finite difference methods.

---

## 📘 Overview

The goal of this project is to:
- Solve the neutron diffusion equation in 2D using Python
- Compare the 2D numerical solution to a corresponding 1D approximation
- Analyze how boundary conditions and geometry affect flux profiles
- Quantify the **relative difference** between the 1D and 2D models

---

## 🧪 Key Features

- Solves both 1D and 2D neutron diffusion equations using finite difference discretization
- Applies mixed boundary conditions:
  - **Vacuum** (zero flux) at `x = 0`, `y = 0`
  - **Reflecting** (zero gradient) at `x = Lx`, `y = Ly`
- Implements the **Successive Over-Relaxation (SOR)** method for solving the 2D system
- Uses **transverse buckling** to approximate leakage in the 1D model
- Includes visualization of:
  - 1D and 2D neutron flux profiles
  - Contour plots of 2D flux
  - Relative difference across spatial domain

---

## 📁 Files

| File | Description |
|------|-------------|
| `diffusion_comparison.ipynb` | Full Jupyter notebook with code, plots, and analysis |
| `diffusion_comparison.pdf` | PDF export of the notebook for convenient review |
| `README.md` | This file – project description and usage |

---

## 🧰 Requirements

You can run this notebook using any standard Python environment (e.g. Jupyter Notebook, Jupyter Lab, VSCode).

### 📦 Suggested Packages:
```bash
numpy
matplotlib
