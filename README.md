# 🐖 Modeling China’s Pork Price Cycle via Hog Age Structure

> *A dynamic population-based approach to modeling pork price fluctuations in China (2007–2034).*

[![Paper DOI](https://img.shields.io/badge/DOI-10.3233/faia230912-blue)](https://doi.org/10.3233/faia230912)

---

## 📘 Project Overview

This repository contains the **full Python implementation and simulation framework** for the paper:

> **Peng, S. (2023)**. *Modeling the pork price cycle in China based on the age structure of hogs.*  
> *Frontiers in Artificial Intelligence and Applications, 373*, 995–1005.  
> DOI: [10.3233/faia230912](https://doi.org/10.3233/faia230912)

### 🎯 Research Goal
To model and predict China's pork price fluctuations by explicitly representing the **age-structured population dynamics of hogs** — integrating **biological reproduction processes** with **economic optimization**.

---

## 🧠 Methodology Summary

1. **Differential Population Modeling**
   - Defined a *continuous-time differential process* to simulate hog reproduction and mortality across age cohorts.
   - Incorporated gestation, maturation, and slaughter rates as dynamic parameters.

2. **Production Optimization**
   - Formulated a *dynamic optimization problem* to determine rational production adjustments based on price feedback.
   - Modeled farmers’ adaptive decisions within biological constraints.

3. **Dynamic Simulation**
   - Integrated models into a unified system using **Python (NumPy + SciPy)**.
   - Simulated pork supply-demand interactions and reproduced historical trends (2007–2034).

4. **Validation**
   - Accurately reproduced historical pork price cycles.
   - Successfully predicted the **downward price trend from 2022 onward**.

---

## 🧩 Repository Structure

## ⚙️ Installation & Usage

### Prerequisites
- Python 3.9+

### Reproduce historical trends (Jupyter Notebook)
jupyter notebook analysis/reproduce_trends.ipynb
