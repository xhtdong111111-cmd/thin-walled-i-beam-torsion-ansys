# P27.7 – Thin-Walled I-Beam Torsion and Warping Analysis

## Project Overview

This project investigates the torsional behavior and warping effects of a thin-walled open-section I-beam using Vlasov's thin-walled beam theory and Finite Element Analysis (FEA) in ANSYS Mechanical.

The study focuses on analytical validation, mesh convergence, geometric nonlinearity, and elastic-plastic material behavior.

## Engineering Model

- **Structure:** Thin-walled I-beam
- **Total length:** 800 mm
- **Overall height:** 200 mm
- **Flange width:** 100 mm
- **Wall thickness:** 3 mm
- **Loading:** Two opposite torque moments of ±1.5 kN·m
- **Boundary condition:** Fixed support at end A

## Methodology

### 1. Analytical Analysis
- Saint-Venant torsion constant calculation.
- Warping constant calculation.
- Vlasov torsion theory.
- Analytical prediction of twist angle.

### 2. Geometry and Finite Element Modeling
- Geometry developed in ANSYS DesignModeler.
- Mesh generation using the Sweep method.
- Quadratic solid elements (SOLID186).
- Boundary conditions and torque loading defined in ANSYS Mechanical.

### 3. Numerical Analysis
- Linear elastic analysis.
- Mesh convergence study.
- Geometric nonlinear analysis using Large Deflection.
- Elastic-plastic material analysis.

## Key Findings

- Linear ANSYS results showed less than 1% deviation from the analytical solution.
- Analytical twist angle at the free end: 0.49977 rad (28.635°).
- A 10 mm mesh was identified as converged in the reported study.
- The 3 mm thickness configuration exhibited 6.667% plastic strain in the nonlinear material analysis.

## Software and Tools

- ANSYS Workbench 2026 R1
- ANSYS Mechanical
- ANSYS DesignModeler
- Vlasov Thin-Walled Beam Theory
- Finite Element Analysis (FEA)

## Project Files

- [Technical Report (PDF)](./K%E1%BA%BFt%20C%E1%BA%A5u%20H%C3%A0ng%20Kh%C3%B4ng.pdf)
- [ANSYS Workbench Archive (.wbpz)](https://drive.google.com/file/d/1uBZFMIjrbGo5diQqN1BCQNm2amkFDVgs/view?usp=drive_link)

## Simulation Gallery

See the images in this repository for geometry, mesh generation, and simulation results.

## Author

Aerospace Engineering Student  
VNU University of Engineering and Technology (UET)

*Academic engineering simulation project. Results are based on the assumptions, material parameters, and boundary conditions documented in the technical report.*
