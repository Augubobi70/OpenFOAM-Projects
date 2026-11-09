# OpenFOAM-Projects
Computational fluid dynamics (CFD) simulations of multiphase flow, built in **OpenFOAM v2506** using the **interFoam** solver (volume-of-fluid method). Each project is on its own branch.

By **Augustine Bobi**, Chemical Engineering, NITC.

## Projects

| Project | Branch | 
|---|---|
| Oil bubble hitting a trapezoidal bluff body | [Oil-Bubble](https://github.com/Augubobi70/OpenFOAM-Projects/tree/Emulsion-of-Oil) |
| Mixing tank with rotating zone (MRF) | [Mixing](https://github.com/Augubobi70/OpenFOAM-Projects/tree/Mixing) |
|Lid Cavity |[Lid-Cavity](https://github.com/Augubobi70/OpenFOAM-Projects/tree/Lid-Cavity) |
|Plane Poisuelle Flow |[Plane-Poisuelle_Flow](https://github.com/Augubobi70/OpenFOAM-Projects/tree/Plane-Poisuelle-Flow) |

## 1. Oil bubble on a bluff body
- **Problem:** how an oil bubble deforms and behaves when it hits a trapezoidal bluff body.
- **Method:** interFoam, non-dimensionalised setup, mesh quality checked with `checkMesh`.
- **Outputs:** area-versus-time chart and animation of the bubble.

## 2. Mixing tank (MRF)
- **Problem:** mixing of water and oil using a rotating zone placed between the two fluids, rotating about the y-axis.
- **Method:** Multiple Reference Frame (MRF) with interFoam, run at 62.8 rpm.
- **Outputs:** animation and CSV data.

## 3. Lid Cavity
- **Problem:** Flow of Newtonian fluid when lid(top) part moves 
- **Method:** IcoFoam is used here. 
- **Outputs:** validation data with ghia dataset

## 4. Poisuelle Flow
- **Problem:** Flow of a Newtonian fluid due to the pressure difference
- **Method:** IcoFoam is used here. 
- **Outputs:** validation data with analytical dataset
## Tools
OpenFOAM v2506 · IcoFoam  ·InterFoam  · Python (post-processing) ·CAD (bluffbody) 

## Contact
- LinkedIn: https://www.linkedin.com/in/augustine-bobi-83927a35a
- GitHub: https://github.com/Augubobi70
