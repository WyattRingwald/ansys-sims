# 🔥 Heat Conduction Simulation

**Type:** Steady-State Thermal  
**Tool:** ANSYS Workbench  
**Project:** 2D conduction with internal heat generation

---

## 🧠 Objective
Model basic heat transfer in a 2D solid with defined thermal boundaries and internal heat generation.

---

## 🛠️ Setup
- Geometry: 2D rectangular plate
- Mesh: Uniform structured grid
- Boundary Conditions:
  - Left face: Fixed temperature
  - Right face: Constant heat flux
- Material: Default thermal solid
- Source: Internal heat generation throughout the domain

---

## 📈 Results
- Temperature contour shows expected gradient
- Vector field confirms directional heat flow
- 1D probe verifies temp drop across the domain

---

## 📂 Visuals
All visuals are available in the `visuals/` folder:
- `Heat_Conduction.mp4` — Temperature gradient animation
- `Vectors.mp4` — Heat flux vector field
- `1D_probe.mp4` — Dynamic probe of temperature vs distance
- `Annotated Geometry View.png` — Geometry + BCs
- `mMsh.png` — Mesh view