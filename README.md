<div align="center">

# Hi, I'm Md. Rifat Khandaker

### Computational Materials Researcher | Chemical Engineer | AI-for-Science Builder

I develop reliable and reproducible computational workflows for materials discovery using density functional theory, atomistic simulation, scientific machine learning, active learning, and uncertainty quantification.

My current work focuses on energy materials, reaction pathways, ionic diffusion, porous materials, 2D systems, and open-source scientific software.

**Research interests:** DFT • Atomistic Simulation • Quantum ESPRESSO • ASE • NEB/CI-NEB • Active Learning • Uncertainty Quantification • MLIPs • Energy Materials • MOFs • 2D Materials

![Python](https://img.shields.io/badge/python-3.11%20%7C%203.12-blue)
![DFT](https://img.shields.io/badge/method-DFT-9cf)
![ASE](https://img.shields.io/badge/simulation-ASE-orange)
![Quantum ESPRESSO](https://img.shields.io/badge/DFT%20engine-Quantum%20ESPRESSO-blueviolet)
![Linux](https://img.shields.io/badge/OS-Linux%20%2F%20WSL-lightgrey)

</div>

---

## About Me

I'm a Chemical Engineering graduate working at the intersection of first-principles simulation and scientific machine learning. I build open-source tools that connect DFT, active learning, uncertainty estimation, and ML interatomic potentials, with applications in energy storage, catalysis, ionic diffusion, and porous materials.

My main focus is computational materials science, supported by hands-on experience in materials synthesis, characterisation, electrochemical testing, and prototype energy-storage systems.

**Education:** B.Sc. in Chemical Engineering, Dhaka University of Engineering & Technology (DUET), Bangladesh
**Location:** Bangladesh

---

## Featured Projects

### [ActiStruct](https://github.com/Rifat19R/ActiStruct)
![Tests](https://img.shields.io/badge/tests-433%20passed%2C%200%20warnings-brightgreen)
![License](https://img.shields.io/badge/license-MIT-green)

Reliability-aware active-learning framework for DFT-guided materials discovery. Combines a Gaussian-process surrogate with a frozen-embedding GNN (SchNet-style encoder) to propose the next DFT candidate under an uncertainty-guided acquisition strategy, while a four-tier escalation system classifies and recovers failed Quantum ESPRESSO runs. Every successful and failed run is recorded in an append-only ledger, with a Streamlit dashboard for monitoring campaigns. Includes a Ti₃C₂-O (MXene) hydrogen-evolution workflow and a 16-record transition-metal-complex reliability benchmark.

This is a development release: 433 tests pass with 0 warnings, but a full closed active-learning loop has not yet been run end-to-end on live DFT data.

`Python` `ASE` `Quantum ESPRESSO` `scikit-learn` `Gaussian Processes` `GNNs` `Streamlit`

---

### [nebwalk](https://github.com/Rifat19R/nebwalk) · [PyPI](https://pypi.org/project/nebwalk/)
![PyPI](https://img.shields.io/pypi/v/nebwalk)
![License](https://img.shields.io/badge/license-MIT-green)

A lightweight, transparent, ASE-compatible NEB / CI-NEB library for computing minimum-energy paths, transition-state barriers, and diffusion mechanisms. Supports linear, IDPP, and regularised-geodesic interpolation, a FIRE optimiser, variable spring constants, and minimum-image handling for periodic systems. Works with any ASE calculator, including Quantum ESPRESSO, VASP, MACE, Egret, and EMT, and includes MLIP-assisted barrier pre-screening with cross-model disagreement selection ahead of DFT refinement, plus automated recovery for failed Quantum ESPRESSO images. Validated on a reproducible H-diffusion-on-Cu(111) benchmark (125.92 meV forward barrier, MACE-MP-0) across 20+ systems and 4 calculators.

Published on PyPI, currently at **v0.10.0**.

`Python` `ASE` `NEB/CI-NEB` `Quantum ESPRESSO` `VASP` `MLIPs`

---

### [MOF CO₂/H₂ Screening](https://github.com/Rifat19R/mof-co2-h2-screening)
![License](https://img.shields.io/badge/license-MIT-green)

Uncertainty-guided machine-learning screening of **278,778 ARC-MOF structures** for pre-combustion CO₂/H₂ separation at 298 K and 40 bar. Predicts CO₂ uptake, working capacity, CO₂/H₂ selectivity, and heat of adsorption using XGBoost as the primary model, with Random Forest, MLP, CGCNN, and a LightGBM-based stacking ensemble as comparisons. Uncertainty is quantified with split conformal prediction, interpreted with SHAP, and combined with Pareto ranking, topology-level design-rule extraction, and synthesizability scoring. The analysis identifies packing efficiency, more than pore diameter, as the primary control on CO₂/H₂ selectivity. Includes a [Zenodo reproducibility archive](https://doi.org/10.5281/zenodo.20305724).

Accepted in *Digital Discovery* (Royal Society of Chemistry).

`Python` `XGBoost` `LightGBM` `CGCNN` `Conformal Prediction` `SHAP`

---

## Ongoing Research

**Computational & AI-driven**
- Reliability-aware DFT automation and failure recovery
- Active learning for materials discovery
- MLIP-assisted reaction-path calculations
- Transition-metal-complex DFT reliability benchmarking
- MXene adsorption and diffusion workflows
- High-throughput porous-material screening

**Energy storage**
- Graphene-based sodium-ion batteries
- Biomass-derived hard-carbon anodes
- CR2032 proof-of-concept cell development, with pouch/cylindrical scale-up planning
- Electrochemical characterisation: CV, EIS, charge-discharge, cycling
- Battery-management-system integration

**Hydrogen & 2D materials**
- Graphene- and borophene-based hydrogen storage concepts
- MXenes and MAX phases
- Surface adsorption, diffusion, and transition pathways in 2D and catalytic systems

*(Items above span validated results, active development, and early-stage research directions — see individual repositories for current status.)*

---

## Technical Skills

**Electronic structure & atomistic simulation**
Quantum ESPRESSO · ASE · VASP · NEB / CI-NEB · DFT workflow design · molecular-dynamics workflow development · Wannier and phonon methods *(active learning direction, not yet production experience)*

**Programming & data**
Python · NumPy · Pandas · SciPy · Matplotlib · scikit-learn · XGBoost · LightGBM · PyTorch · Streamlit · Git · GitHub Actions · YAML · JSON/JSONL

**Scientific machine learning**
Gaussian processes · graph neural networks · SchNet-style embeddings · active learning · Bayesian acquisition · uncertainty quantification · conformal prediction · SHAP · MLIPs · MACE

**Computing environment**
Linux · WSL · Conda · HPC workflow preparation · MPI · reproducible environments · automated testing · CI/CD for scientific software

---

## Research Experience

- **Co-Principal Investigator and Computational Lead** on multiple World Bank / EDGE-supported energy-storage R&D projects.
- Combine computational modelling with experimental materials research; coordinate research tasks, computational analysis, reporting, and technical documentation.
- International research collaboration experience in computational materials and nanomaterials.

**Experimental exposure** *(supporting the computational focus above)*: graphene and carbon-material synthesis, CR2032 coin-cell assembly, XRD, FESEM/SEM-EDS, Raman, FTIR, TGA-DSC, BET, battery testing, and BMS development.

---

## Publications, Manuscripts & Research Outputs

1. **Packing Efficiency Governs CO₂/H₂ Selectivity in Machine-Learning-Screened MOFs**
   Md. Rifat Khandaker, Mohammad Asaduzzaman Chowdhury, Sujan Hossain
   Manuscript in preparation, target journal *Digital Discovery* (RSC)
   [Repository](https://github.com/Rifat19R/mof-co2-h2-screening) · [Zenodo](https://doi.org/10.5281/zenodo.20305724)

Selected collaborative manuscripts and book chapters — bibliographic details to be added after verification.

---

## Funded Research & Recognition

- Co-PI on two World Bank / EDGE-supported energy-storage R&D projects
- Research spanning graphene-based energy storage and prototype transport/energy systems
- **Bicchuron 2.0** finalist — top 7 among 700+ participants
- Experience in scientific leadership, computational analysis, proposal development, and research reporting

---

## Current Direction

I am currently building open-source tools that connect first-principles simulation, active learning, uncertainty estimation, ML interatomic potentials, and automated decision-making. My long-term goal is to help reduce the time from a scientific question to a validated computational answer.

I am particularly interested in collaborations involving energy materials, catalytic surfaces, ionic diffusion, transition pathways, porous materials, and autonomous computational research.

---

## Collaboration & Contact

I am open to research collaboration in DFT, atomistic simulation, AI for materials, scientific software, energy storage, catalysis, MOFs, and 2D materials.

- Email: [rifatkh.duet@gmail.com](mailto:rifatkh.duet@gmail.com)
- GitHub: [@Rifat19R](https://github.com/Rifat19R)

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Rifat19R&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Rifat19R&layout=compact&hide_border=true&theme=default)

</div>
