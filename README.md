# OpenFOAM-Projects
Computational fluid dynamics (CFD) simulations of multiphase flow, built in **OpenFOAM v2506** using the **interFoam** solver (volume-of-fluid method). Each project is on its own branch.

By **Augustine Bobi**, Chemical Engineering, NITC.

## Projects

| Project | Branch | Summary |
|---|---|---|
| Oil bubble hitting a trapezoidal bluff body | [branch-name-1](https://github.com/Augubobi70/OpenFOAM-Projects/tree/Emulsion-of-Oil) |
| Mixing tank with rotating zone (MRF) | [branch-name-2](https://github.com/Augubobi70/OpenFOAM-Projects/tree/Mixing) |

## 1. Oil bubble on a bluff body
- **Problem:** how an oil bubble deforms and behaves when it hits a trapezoidal bluff body.
- **Method:** interFoam, non-dimensionalised setup, mesh quality checked with `checkMesh`.
- **Outputs:** area-versus-time chart and animation of the bubble.
- **Key finding:** [one sentence with a number, e.g. what changed with Reynolds number]

## 2. Mixing tank (MRF)
- **Problem:** mixing of water and oil using a rotating zone placed between the two fluids, rotating about the y-axis.
- **Method:** Multiple Reference Frame (MRF) with interFoam, run at 62.8 rpm.
- **Outputs:** animation and CSV data.
- **Key finding:** [one sentence comparing the two rpm cases]

## Tools
OpenFOAM v2506 · interFoam · MRF · checkMesh · Python (post-processing and plots)

## Contact
- LinkedIn: https://www.linkedin.com/in/augustine-bobi-83927a35a
- GitHub: https://github.com/Augubobi70
