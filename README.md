# Gingerbreadman Map Analysis with Stochastic Perturbations

This repository contains a **numerical and computational study** of a **piecewise linear map under stochastic perturbations**, based on a generalization of the classical "Gingerbreadman" map studied by **Robert L. Devaney in 1984**.  

The work is part of a research investigation, with a **PDF report** included in this repository detailing the theoretical and computational aspects.

---

## 🧩 Background

The **Gingerbreadman map**, introduced by Robert L. Devaney in 1984, is a simple but rich example of a **piecewise linear chaotic map** in discrete dynamical systems.  

In this project, the model is **generalized and studied under stochastic perturbations**, allowing exploration of how random fluctuations affect the dynamics.  

Key objectives include:

- Investigating the **stability and behavior** of the generalized map.
- Visualizing trajectories under different perturbation strengths.
- Exploring **chaotic and quasi-periodic regimes** numerically.

---

## 📂 Repository Structure

- `Piecewise_Linear_Map_Under_Stochastic_Perturbations.ipynb` → Jupyter notebook implementing the generalized map and stochastic simulations.  
- `DOcumentación Exploración en las Dinámicas.pdf` → Detailed PDF report of the study and theoretical background.  

---

## 🖥️ Jupyter Notebook Features

- Implements a **piecewise linear map** with tunable parameters.
- Introduces **stochastic perturbations** at each iteration.
- Generates **trajectories and phase-space visualizations**.
- Provides **interactive plots** using `matplotlib` for numerical exploration.
- Includes commentary and explanations of the mathematical model and results.

---

## ⚙️ Requirements

Python 3.8+ with the following libraries:

- `numpy`
- `matplotlib`
- `pandas`
- `ipywidgets` (optional for interactive exploration)
- `scipy` (if used for random perturbations or additional computations)

Install dependencies using pip:

```bash
pip install numpy matplotlib ipywidgets scipy
