# Bioinspired Spiral Flow Arterial Graft

## Overview
This project focuses on the design and simulation of a bioinspired spiral flow arterial graft using SolidWorks as the primary CAD and CFD tool. The design emulates natural helical blood flow patterns to reduce turbulence, prevent thrombosis, and enhance endothelial cell response, particularly in peripheral vascular bypass procedures.

## Objective
To create a spiral ridge design along the inner lumen of a cylindrical graft that promotes spiral blood flow, thereby improving hemodynamic efficiency and reducing stagnation zones commonly found in conventional straight grafts.

## Design Methodology
- **Software Used**: SolidWorks (Part Modeling + Flow Simulation)
- **Graft Geometry**:
  - Outer Diameter: 6 mm
  - Length: 100 mm
  - Wall Thickness: 1 mm
  - Spiral Ridge Height: 0.5 mm
  - Spiral Pitch: 20 mm (one full turn every 20 mm)
- **Material**: Expanded Polytetrafluoroethylene (ePTFE), a biocompatible polymer widely used in vascular grafts.
- **Spiral Ridge**: Modeled as an internal helical structure wrapping along the lumen from end to end.

## Simulation Setup
- **Fluid**: Blood (modeled as non-Newtonian, Carreau model)
- **Inlet Velocity**: 0.3 m/s (pulsatile flow modeled in time steps)
- **Boundary Conditions**: No-slip walls, physiological pressure gradient from inlet to outlet
- **Meshing**: Fine mesh with refinement near the ridge and lumen wall
- **Solver Settings**: Transient analysis with time-step resolution for pulsatile behavior

## Results
- Flow streamlines followed the helical path with minimal recirculation
- Wall shear stress distribution was more uniform compared to cylindrical graft
- 20–25% predicted increase in endothelial cell coverage based on WSS profile
- Indications of delayed onset of thrombosis-prone zones

## Future Scope
- Experimental validation of CFD results using in vitro flow loop setups
- Customization of spiral pitch and ridge profile based on patient-specific data
- Integration with FEA for fatigue and compliance mismatch analysis
