<!--
GitHub profile README for Rifat19R.
GitHub-flavored Markdown + supported HTML only. No repository-local assets.
All HTML-only blocks are self-contained; Markdown begins outside each block.
--><p align="center">
  <img width="100%" alt="Md. Rifat Khandaker | Computational Materials Scientist" src="https://capsule-render.vercel.app/api?type=rect&amp;height=190&amp;color=0:07111F,46:102B43,100:075E69&amp;text=Md.%20Rifat%20Khandaker&amp;fontSize=41&amp;fontColor=EAFBFF&amp;fontAlignY=39&amp;desc=COMPUTATIONAL%20MATERIALS%20SCIENTIST%20%20%7C%20%20AI%20FOR%20SCIENCE&amp;descSize=16&amp;descAlignY=64&amp;animation=fadeIn" />
</p><p align="center">
  <strong>First-principles modelling · Scientific machine learning · Research software engineering</strong>
</p><p align="center">
  <a href="https://github.com/Rifat19R"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Rifat19R-111827?style=for-the-badge&amp;logo=github&amp;logoColor=white" /></a>
  <a href="https://pypi.org/project/NEBwalk/"><img alt="NEBwalk on PyPI" src="https://img.shields.io/pypi/v/NEBwalk?style=for-the-badge&amp;label=NEBwalk&amp;color=0891b2" /></a>
  <a href="https://rifat19r.github.io/NEBwalk/"><img alt="Documentation" src="https://img.shields.io/badge/Read-Documentation-155e75?style=for-the-badge&amp;logo=readthedocs&amp;logoColor=white" /></a>
  <a href="mailto:rifatkh.duet@gmail.com"><img alt="Contact" src="https://img.shields.io/badge/Research-Contact-0f766e?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" /></a>
</p>The work
I develop computational materials science software that connects density functional theory (DFT), atomistic simulations, machine-learned interatomic potentials (MLIPs) and scientific machine learning. My research spans catalytic surfaces, atomic migration and transition states, energy storage, MXenes, and porous materials.

My engineering priority is simple: a working pipeline is not automatically a validated scientific result. I build reproducible workflows that preserve this distinction.
<table>
  <tr>
    <td align="center" width="33%"><b>ATOMISTIC PHYSICS</b><br/><sub>NEB · CI-NEB · DFT · MLIPs</sub></td>
    <td align="center" width="33%"><b>INTELLIGENT SEARCH</b><br/><sub>Active learning · GP · GNN</sub></td>
    <td align="center" width="33%"><b>SCIENTIFIC TRUST</b><br/><sub>Verification · Provenance · OOD testing</sub></td>
  </tr>
</table>01 / Featured research software
<table>
  <tr>
    <td valign="top" width="50%">
      <h3><a href="https://github.com/Rifat19R/NEBwalk">NEBwalk</a></h3>
      <p><b>Atomistic pathways &amp; activation barriers</b></p>
      <p>ASE-compatible NEB/CI-NEB for surface diffusion, defect migration and reaction pathways, with MLIP-assisted screening, Quantum ESPRESSO integration and resumable MACE–QE campaigns.</p>
      <p><sub><b>Evidence:</b> v0.11.0 · 13 retained audited benchmarks. Sparse DFT labels do not replace complete DFT NEB validation.</sub></p>
      <a href="https://github.com/Rifat19R/NEBwalk">Source</a> · <a href="https://rifat19r.github.io/NEBwalk/">Docs</a> · <a href="https://pypi.org/project/NEBwalk/">PyPI</a>
    </td>
    <td valign="top" width="50%">
      <h3><a href="https://github.com/Rifat19R/ActiStruct">ActiStruct</a></h3>
      <p><b>Reliability-aware DFT active learning</b></p>
      <p>Explores targeted material configurations using GP/GNN-based acquisition, QE failure diagnosis and recovery, and traceable run records. Includes MXene H-adsorption and transition-metal-complex case studies.</p>
      <p><sub><b>Evidence:</b> v2.0.0 · real QE experiments and offline tests. High-fidelity ranking validation is incomplete.</sub></p>
      <a href="https://github.com/Rifat19R/ActiStruct">Source</a> · <a href="https://github.com/Rifat19R/ActiStruct/tree/main/benchmarks">Benchmarks</a>
    </td>
  </tr>
  <tr>
    <td valign="top" colspan="2">
      <h3><a href="https://github.com/Rifat19R/Alchemist_MCP">Alchemist-MCP</a></h3>
      <p><b>Verification-first DFT → MLIP infrastructure</b></p>
      <p>A fail-closed MCP toolkit for QE provenance and unit checks, dataset integrity, controlled training plans, energy/force/barrier comparisons and evidence-based validation gates. Intended to complement, not duplicate, scientific engines such as NEBwalk.</p>
      <p><sub><b>Evidence:</b> engineering tests and demonstration are documented; production scientific validation of migration barriers is pending.</sub></p>
      <a href="https://github.com/Rifat19R/Alchemist_MCP">Source</a> · <a href="https://github.com/Rifat19R/Alchemist_MCP#what-is-validated-today">Validation status</a>
    </td>
  </tr>
</table>02 / Applied materials research
Project	Scientific application	Reproducibility
MOF CO₂/H₂ Screening	ML screening of 278,778 ARC-MOF structures for pre-combustion gas separation. Uncertainty assessment, SHAP, Pareto screening and topology analysis.	Code · Zenodo. Database-based evaluation, not experimental confirmation.
Solid-Electrolyte Validation	Evaluating whether internal ML validation predicts transfer to new lithium solid-electrolyte chemistries.	Code & evidence. Prespecified family-aware-validation hypotheses were not supported.


03 / From a materials question to defensible evidence
Materials question  →  Atomic model / curated dataset
                              │
                      DFT / reference data
                              │
                ┌─────────────┴─────────────┐
                │                           │
          NEBwalk                      ActiStruct
       Reaction pathways          Candidate exploration
                └─────────────┬─────────────┘
                              │
                   Verification & evaluation
                  (Alchemist-MCP interfaces)
                              │
                Reproducible scientific evidence
The diagram shows the intended division of responsibilities. These are independent repositories; full cross-project integration has not been established.
04 / Technical expertise
Area	Methods and tools
Electronic structure	Quantum ESPRESSO · VASP · ASE · DFT · adsorption energetics · NEB / CI-NEB
Scientific ML	PyTorch · MACE · Gaussian processes · GNNs · Bayesian/active learning · scikit-learn · XGBoost
Scientific reliability	Data provenance · independent DFT references · group/OOD validation · uncertainty assessment · regression testing
Software engineering	Python · Linux/WSL · Git/GitHub · CI/CD · reproducible workflows · APIs · CLI tools


05 / Research experience & current directions
- Co-Principal Investigator on two World Bank/EDGE-supported energy-storage R&D initiatives, bridging computational research and experimental materials work.
- Experience with materials characterization and electrochemical methods, including XRD, electron microscopy/EDS, Raman, FTIR, BET, CV/EIS and coin-cell prototyping.
- Currently interested in computational catalysis, MLIP-assisted reaction mechanisms, ionic transport, sodium-ion energy materials, 2D systems, and trustworthy AI for science.
Scientific practice: A converged calculation, a passing software test and a physically validated prediction are three separate claims. Each requires its own evidence.

<p align="center">
  <strong>Open to scientific collaborations, research software development and computational materials projects.</strong>
</p><p align="center">
  <a href="mailto:rifatkh.duet@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Research%20collaboration-0f766e?style=flat-square&amp;logo=gmail&amp;logoColor=white" /></a>
  <a href="https://github.com/Rifat19R"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Rifat19R-111827?style=flat-square&amp;logo=github&amp;logoColor=white" /></a>
</p><p align="center"><sub>Bangladesh · Computational Materials Science · Open-source Scientific Software</sub></p>
