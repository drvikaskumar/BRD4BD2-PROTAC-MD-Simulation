# BRD4BD2-PROTAC-MD-Simulation
This repository contains input files, modeled structures, and simulation outputs used in the study:

**"Structural Insights into BRD4BD2-MZ1/AT1 Complexes for Targeted Protein Degradation via Molecular Dynamics Simulations"**

## Project Description

This study investigates the structural and dynamic behavior of ternary complexes formed by BRD4BD2 with MZ1 and AT1 PROTACs, in complex with VHL, Cullin2-RBX1, and E2-Ubiquitin ligase machinery. Molecular dynamics simulations were performed to analyze conformational flexibility, stability, and free energy landscapes of the systems.

## Repository Structure
## Contents

Each system folder (`MZ1` and `AT1`) contains:

### Input/
- `.pdb` files: Ligands and modeled protein complexes
- `.itp` files: Ligand topology generated using SwissParam
- `.mdp` files: GROMACS simulation parameter files for EM, NVT, NPT, and MD runs

### Output/
- `Avg_complex_*.pdb`: Representative average structures at various simulation time points
- `rmsd_*.xvg`, `rmsf.xvg`: Root-mean-square deviation/fluctuation plots
- `eigenval.xvg`, `proj-1-2.xvg`: Principal Component Analysis
- `gibbs.eps/xpm`: Free Energy Landscape plots
- `gyrate`, `Hbonds`, and distance analyses between key residues

## Tools & Methods

- **MD Simulation Software**: GROMACS v5.1.5
- **Force Field**: CHARMM27 (with TIP3P water model)
- **Ligand Parameters**: Generated using [SwissParam](http://www.swissparam.ch/)
- **Modeling Tools**: Discovery Studio and HADDOCK web server
- **Trajectory Analysis**: GROMACS tools (`gmx rms`, `gmx rmsf`, `gmx covar`, `gmx sham`), VMD

## 📊 PDB Structures Used

- BRD4BD2-MZ1-VHL: [5T35](https://www.rcsb.org/structure/5T35)
- Cullin2-RBX1: [5N4W](https://www.rcsb.org/structure/5N4W)
- E2-Ubiquitin: [2FUH](https://www.rcsb.org/structure/2FUH)

## Contact
For questions or requests:
**Vikas Kumar**  
Postdoctoral Researcher, BCMaterials, Spain  
✉️ vikaspathania777@gmail.com
---

## License

This data is provided for academic and research use only.

