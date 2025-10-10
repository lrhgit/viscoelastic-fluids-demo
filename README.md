# Viscoelastic Fluids Demo

This repository contains interactive notebooks illustrating **viscoelastic fluid behavior** using the **Maxwell model** (and later possibly Kelvin–Voigt, Jeffreys, and Oldroyd-B).

## 📘 Current notebook
### Maxwell Model – Creep and Stress Relaxation
The Maxwell model combines:
- A spring (elastic modulus G)
- A dashpot (viscosity η)
- Characteristic relaxation time λ = η / G

The notebook demonstrates:
- **Stress relaxation:** σ(t) = Gγ₀ e^{-t/λ}
- **Creep:** γ(t) = σ₀/G + (σ₀/η)t

## ▶️ Open in Google Colab
Click to open directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lrhgit/viscoelastic-fluids-demo/blob/main/notebooks/maxwell_model.ipynb)

## Requirements
```bash
pip install -r requirements.txt
