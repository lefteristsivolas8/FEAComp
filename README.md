# FEAComp — Finite Element Analysis & Composites for iPad

**FEAComp** is a professional-grade finite element analysis and composite
materials app designed for iPad. It brings desktop-level simulation
capabilities to a touch-first interface for engineers, researchers,
and students.

---

## Features

- **CAD & Geometry** — 2D sketch tools, solid extrusion, boolean operations,
  and STEP import powered by OpenCASCADE Technology
- **Meshing** — Automatic surface triangulation and tetrahedral volume mesh
  generation; STL import/export
- **Thermal Analysis** — Steady-state and transient heat conduction with
  temperature-dependent properties and Newton-Raphson nonlinear iteration
- **Structural Analysis** — Linear elastic and incremental pseudo-static
  analysis; isotropic, transversely isotropic, and orthotropic materials
  with arbitrary orientations
- **Thermo-Mechanical Coupling** — Sequential thermal-to-structural solve
  with per-step history
- **Homogenization** — Mori-Tanaka + Voigt mean-field homogenization for
  elastic, thermo-elastic, and elasto-plastic composite material properties
- **Results & Post-Processing** — Interactive colourmap rendering of
  temperature, displacement, von Mises stress, directional stresses, safety
  factor, and mesh quality; element probe; reaction forces
- **Import / Export** — Abaqus (.inp) and Nastran (.bdf) with MPCs,
  orientations, and tie constraints; PDF verification report generation

---

## Support & Bug Reports

Found a bug or have a feature request?  
**[Open an Issue](../../issues/new/choose)** and use the appropriate template.

Please include:
- A brief description of the problem or request
- Steps to reproduce (for bugs)
- iPad model and iOS version
- A screenshot or project file if relevant

---

## Frequently Asked Questions

**What is the free tier?**  
The free tier supports meshes up to 5,000 degrees of freedom with static
thermal and structural analysis. A Pro subscription unlocks unlimited DOFs,
transient and thermo-mechanical analysis, homogenization, and
Abaqus/Nastran export.

**Can I use FEAComp for real engineering design?**  
FEAComp is intended for educational, research, and preliminary analysis
purposes. All results must be independently verified by qualified engineers
using validated, certified software before and the results should not be used for 
any practical application. Please read the full Terms of Use shown at first launch.

**Which file formats are supported?**  
Import: Abaqus `.inp`, Nastran `.bdf`/`.nas`, STL  
Export: Abaqus `.inp`, Nastran `.nas`, STL, FEAComp project `.femproj`,
PDF report

---

## Open-Source Acknowledgements

FEAComp is built on several open-source libraries:

| Library | License |
|---------|---------|
| [OpenCASCADE Technology (OCCT) 7.7.2](https://dev.opencascade.org) | LGPL-2.1 |
| [PMP — Polygon Mesh Processing Library](https://www.pmp-library.org) | MIT |
| [Eigen 3.x](https://eigen.tuxfamily.org) | MPL-2.0 |
| [Quartet](https://github.com/crawforddoran/quartet) | ISC |
| Apple Accelerate / Sparse BLAS | Apple SDK License |

---

## Privacy

FEAComp collects **no personal data**, analytics, or crash reports.
All computation happens entirely on-device.  
[Privacy Policy](PRIVACY.md)

