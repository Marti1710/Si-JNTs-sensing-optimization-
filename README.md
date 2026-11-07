# Si-JNTs-sensing-optimization-

# Langmuir Adsorption & Electrical Sensor Modelling

A Julia simulation toolkit for modelling gas-phase adsorption kinetics, lateral interaction energy corrections, and drain current ($I_{\text{drain}}$) responses on surface-functionalised silicon platforms.

### Overview
This repository contains numerical scripts to simulate sensor behaviour across different target gases ($\text{CH}_4$, $\text{H}_2\text{O}$, $\text{NH}_3$, $\text{NO}_2$):
- **Physical Constants:** Baseline parameters and reference resistances.
- **Interaction Energies:** Lateral adsorbate–adsorbate interaction energy correction terms.
- **Monolayer Kinetics:** Time-evolution of surface coverage ($\theta$) and signal intensity.
- **Drain Current ($I_{\text{drain}}$):** Linear and coverage-dependent $I\text{–}V$ characteristic curves.
- **Parameter Optimisation:** Sensitivity exploration across environmental conditions.

## Requirements
- **Julia** (v1.9+)
- `Plots.jl` for generating $I\text{–}V$ and kinetic response curves.
