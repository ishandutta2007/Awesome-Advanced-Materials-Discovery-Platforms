# Awesome-Advanced-Materials-Discovery-Platforms

# Top Advanced Materials Discovery Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI-Driven Materials Informatics, Generative Design & Autonomous Experimentation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Advanced Materials Discovery**. These tools enable researchers and organizations to accelerate the discovery of novel materials—from batteries and catalysts to semiconductors and resilient synthetics—using machine learning, generative models, and autonomous experimentation.

**Examples** include Citrine Informatics, Kebotix, Schrödinger, Materials Project, Enthought, Aionics, Qubit Pharmaceuticals, SandboxAQ, Mat3ra, and Noble.AI (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom property prediction, and open materials databases—ideal for researchers, materials scientists, and developers seeking transparent, vendor-independent discovery platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Citrine Informatics](https://citrine.io/)**  
  AI-powered materials and chemicals informatics platform. Features data aggregation from experiments and simulations, machine learning model training, and active learning to prioritize high-value experiments. Used by Fortune 500 materials companies for accelerating R&D cycles.

- **[Kebotix](https://www.kebotix.com/)**  
  AI-driven autonomous materials discovery platform. Combines generative models, robotics, and high-throughput experimentation to discover new chemicals and materials for sustainability applications. Closed-loop approach from hypothesis to validation.

- **[Schrödinger](https://www.schrodinger.com/)**  
  Computational platform for molecular modeling and materials science. Features physics-based simulation, machine learning, and predictive analytics for drug discovery and materials design. Widely used in pharmaceutical and specialty chemicals R&D.

- **[Materials Project](https://materialsproject.org/)**  
  Open-access database of computed materials properties maintained by Lawrence Berkeley National Laboratory. Surpassed 650,000 registered users with 200,000+ materials and 577,000+ molecules. Provides standardized, machine-learning-ready datasets that eliminate months of data preparation. Cited 32,000+ times in peer-reviewed literature. API access available for programmatic queries.

- **[Enthought](https://www.enthought.com/)**  
  Materials informatics and data science platform. Features Materials Knowledge Center, machine learning workflows, and custom analytics for R&D organizations. Focus on bridging simulation and experimental data.

- **[Aionics](https://aionics.io/)**  
  AI platform for battery materials discovery. Features electrolyte and electrode optimization, machine learning force fields, and ionic conductivity prediction. Targets faster development cycles for next-generation batteries.

- **[Qubit Pharmaceuticals](https://www.qubit-pharmaceuticals.com/)**  
  Quantum-accelerated drug discovery platform. Combines quantum chemistry, molecular dynamics, and AI to accelerate lead identification and optimization for pharmaceutical applications.

- **[SandboxAQ](https://www.sandboxaq.com/)**  
  AI and quantum technology platform with materials science applications. Features simulation acceleration, generative design, and property prediction for advanced materials including semiconductors and alloys.

- **[Mat3ra](https://www.mat3ra.com/)**  
  Cloud platform for materials modeling and simulation. Features DFT calculations, machine learning potentials, and automated workflows for screening materials across the periodic table.

- **[Noble.AI](https://www.noble.ai/)**  
  AI-driven R&D platform for materials and chemicals. Features automated experimentation, Bayesian optimization, and knowledge extraction from scientific literature and lab data.

## Open-Source GitHub Projects

- **[DeepChem](https://github.com/deepchem/deepchem)**  
  Open-source Python framework (MIT) for deep learning on molecular and materials data. 5k+ GitHub stars. Features featurizer-pipeline abstraction converting raw molecular data into numerical representations including graph-based structures and SMILES tokenization. Handles datasets exceeding RAM via disk-sharded persistence. Includes molecular docking workflows for drug discovery and materials science applications.

- **[MatterGen (Microsoft)](https://github.com/microsoft/mattergen)**  
  Official implementation of MatterGen (MIT) — a generative model for inorganic materials design across the periodic table. Can be fine-tuned to steer generation toward specific property constraints. Enables design space exploration beyond traditional trial-and-error approaches.

- **[SMACT](https://github.com/wmd-group/smact)**  
  Semiconducting Materials from Analogy and Chemical Theory (MIT). Python library for rapid screening and informatics-based structure prediction. Uses chemical element data to filter and prioritize materials candidates. 102 stars on GitHub with 5,680+ monthly PyPI downloads.

- **[AtomGPT](https://github.com/usnistgov/atomgpt)**  
  Atomistic generative pre-trained transformer (NIST) for forward and inverse materials design. Features both property prediction from structure (forward) and structure generation from properties (inverse). Uses text descriptions of materials for efficient property prediction comparable to graph neural networks. Includes DiffractGPT for generating structures from XRD spectra. Validated through DFT calculations.

- **[Aviary](https://github.com/CompRhys/aviary)**  
  Framework for materials property prediction and discovery under a common interface. Focus on coordinate-free deep learning models for crystal structure prediction. Part of the Roost ecosystem for representation learning from stoichiometry.

- **[CSPML](https://github.com/minoru938/cspml)**  
  Crystal Structure Prediction by Machine Learning (license varies). Binary classification neural network predicts stable structures for any query composition by selecting from crystal structure databases. Alternative to TCSP 2.0 which achieves 78.33% StructureMatcher accuracy.

- **[matminer](https://github.com/hackingmaterials/matminer)**  
  Open-source Python toolkit (MIT) for materials data mining. Features data retrieval from Materials Project and other databases, featurization for machine learning, and integration with pymatgen. Widely used for building ML-ready materials datasets.

- **[LeMaterial](https://github.com/LeMaterial)**  
  Open-source initiative (Hugging Face) for materials discovery with community-driven datasets. Features efficient fingerprinting algorithm for de-duplication—Carbon-24 dataset processed in 100 seconds vs 17 hours with Pymatgen's StructureMatcher. Links materials across databases and enables phase diagram exploration. Aims to gather curated datasets and benchmark ML models.

- **[D2GNN (Sandia)](https://github.com/sandialabs/d2gnn)**  
  Defect Diffusion Graph Neural Networks (MIT) for discovering materials for high-temperature, clean-energy applications. Models relationship between material structures and defect properties. Accelerates development of innovative materials for energy applications.

- **[JARVIS (NIST)](https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks)**  
  Data-driven platform from NIST for materials discovery and optimization. Integrates DFT, classical force fields, machine learning, and quantum computing. Provides JARVIS-DFT and JARVIS-FF datasets plus JARVIS-Leaderboard for benchmarking. Essential for reproducible computational materials science.

- **[HypoGen (PNNL)](https://github.com/pnnl/hypogen)**  
  Workflow for automatic knowledge discovery in materials science (BSD-2-Clause). Combines experimental automation with advanced ML and AI techniques. Enables autonomous hypothesis generation and validation.

- **[MatBench Discovery](https://github.com/janosh/matbench-discovery)**  
  Evaluation framework for ML models simulating high-throughput materials discovery (MIT). 152+ GitHub stars. Benchmarks machine learning interatomic potentials and property prediction models against standardized tasks.

### Additional Strong Open-Source Options

- **[mat_discover](https://github.com/sparks-baird/mat_discover)** — Materials discovery algorithm for exploring high-performance candidates in new chemical spaces.
- **[CrabNet](https://github.com/sparks-baird/CrabNet)** — Predict materials properties using only composition information (attention-based neural network).
- **[MAML](https://github.com/materialsvirtuallab/maml)** — Python for Materials Machine Learning with descriptors, force fields, and deep learning models. 412 GitHub stars.
- **[MACE](https://github.com/ACEsuit/mace)** — State-of-the-art machine learning interatomic potential for molecular dynamics with first-principles accuracy.
- **[CHGNet](https://github.com/CederGroupHub/chgnet)** — Universal machine learning potential for charge-informed atomistic modeling.
- **[ASE](https://gitlab.com/ase/ase)** — Atomic Simulation Environment for setting up, running, and analyzing atomistic simulations.
- **[pymatgen](https://github.com/materialsproject/pymatgen)** — Python Materials Genomics for materials analysis and integration with Materials Project.
- Community **n8n** workflows for materials data pipeline automation and experiment tracking.

**Frameworks for building custom systems**: Combine **MatterGen** or **AtomGPT** for generative materials design with **matminer** and **pymatgen** for data preparation, **MACE** or **CHGNet** for machine learning potentials, **DeepChem** for property prediction, and **LeMaterial** for de-duplicated datasets—creating a fully self-hosted, enterprise-grade materials discovery platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Materials discovery platforms handling experimental data must comply with data protection and intellectual property regulations where applicable.
- Self-hosted open-source solutions require proper computational infrastructure (GPU resources for ML models), domain expertise for validation, and ongoing maintenance. Predicted materials require experimental synthesis and characterization before practical application—computational discovery is a hypothesis generation tool, not a replacement for laboratory validation.

---

**Made for materials scientists, computational chemists, R&D engineers, and developers building transparent materials discovery solutions.**  
Let's make Advanced Materials Discovery more open, data-driven, and accelerated.
