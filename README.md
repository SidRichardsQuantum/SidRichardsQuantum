# 👋 Hi, I'm Sid Richards
**Quantum Computing Research Engineer**
Focused on quantum algorithms (VQE, QPE, Shor), numerical simulation, and physics-driven modelling, with an emphasis on building practical PyPI packages.

I have a First Class MSci in Theoretical Physics & Mathematics from Lancaster University and I build research-grade open-source projects across quantum computing, photonics, numerical methods, and applied optimisation.
My work spans quantum chemistry, quantum error mitigation, classical simulations of quantum algorithms, and high-performance scientific modelling.

I'm currently in Sydney, Australia with a working holiday VISA (subclass 417), looking for work!

---

## 🚀 Featured Projects

### [**Variational Quantum Algorithms for Quantum Chemistry (VQE, QPE, QITE) (Work in Progress)**](https://github.com/SidRichardsQuantum/Variational_Quantum_Eigensolver)
A modular, reproducible PennyLane-based **quantum chemistry simulation suite** for small-molecule benchmarks (H₂, LiH, H₂O, H₃⁺), shipped as a versioned Python package with CLI tooling and consistent caching.
- VQE (ground state) + **ADAPT-VQE**
- Excited states: **LR-VQE (tangent-space / TDA)**, **QSE**, **SSVQE**, **VQD**
- **QPE** (noisy + noiseless) and **VarQITE/QITE** (McLachlan updates)
- Unified `common/` layer: Hamiltonians, molecule registry, geometry scans, plotting, persistence
- PyPI: [vqe-pennylane](https://pypi.org/project/vqe-pennylane/)

### [**Quantum Machine Learning (QML) (Work in Progress)**](https://github.com/SidRichardsQuantum/Quantum_Machine_Learning)
Reusable quantum machine learning library built on PennyLane, engineered with the same modular architecture as my VQE toolkit.
- Variational Quantum Classifier (VQC) with configurable ansatz layers and optimizers
- Quantum kernel workflows integrated with sklearn SVC
- Variational regression with standardized training and evaluation pipelines
- Deterministic experiment configs, structured result persistence, and consistent plotting utilities
- CLI + API workflows; notebooks serve as thin usage examples
- PyPI: [qml-pennylane](https://pypi.org/project/qml-pennylane/)

### [**Portfolio Optimisation via VQE & QAOA**](https://github.com/SidRichardsQuantum/VQE_Portfolio_Optimization)
Quantum optimisation toolkit for portfolio problems, engineered as a clean Python library (notebooks are thin clients).
- **Binary selection**: cardinality-constrained QUBO/Ising formulation solved with **VQE and QAOA**
- **Fractional allocation**: simplex-constrained ansatz for long-only weights (constraint by construction)
- QUBO → Ising Hamiltonian pipeline from covariance matrices and expected returns
- CLI + API workflows, λ-sweeps, efficient frontier utilities
- PyPI: [vqe-portfolio](https://pypi.org/project/vqe-portfolio/)

### [**Quantum Singular Value Transformation (QSVT)**](https://github.com/SidRichardsQuantum/Quantum_Singular_Value_Transformation)
Lightweight PennyLane-based toolkit for **spectral transformations via bounded polynomials**, designed to make **Quantum Singular Value Transformation (QSVT)** more experimentally accessible through reusable Python components.
- Polynomial functional calculus perspective on QSVT and QSP
- Bounded polynomial design utilities (Chebyshev approximations, sign, inverse-like, filters)
- Thin wrappers around PennyLane QSVT primitives for scalar and diagonal transforms
- Classical spectral reference implementations for verification and intuition
- Modular utilities for reusable polynomial workflows
- CLI + API workflows; notebooks emphasise spectral interpretation and reproducibility
- PyPI: [qsvt-pennylane](https://pypi.org/project/qsvt-pennylane/)

### [**Dynamics of Topological Photonics**](https://github.com/SidRichardsQuantum/Dynamics_of_Topological_Photonics)
A full simulation suite exploring nonlinear gain/loss, edge modes, and stability regimes in non-Hermitian topological lattices (NRSSH & Diamond models).
Includes phase diagrams, time-evolution solvers, Hamiltonian construction, and analysis relevant to photonics, nonlinear optics, and topological quantum systems.
This is revamped code from my uni dissertation: "Dynamics of Topological Photonics with Nonlinear Saturable Gain and Loss".

### [**Shor’s Algorithm – Classical Quantum Circuit Simulation**](https://github.com/SidRichardsQuantum/Shors_Algorithm_Simulation)
A pure-Python, matrix-based classical simulation of Shor’s quantum factoring algorithm.
Implements superposition, modular exponentiation, IQFT, probability visualisation, runtime scaling, and educational tooling without relying on quantum frameworks.

### [**Celestial Dynamics – Iteration Methods Comparison**](https://github.com/SidRichardsQuantum/Celestial_Dynamics_Iteration_Methods)
A numerical physics project comparing Euler, Midpoint, Heun, and RK4 schemes through gravitational simulations.
Includes projectile motion, two-body and three-body orbits, chaos behaviour, and energy-conservation analysis implemented primarily in R.

### [**Quantum Error Correction (Work in Progress)**](https://github.com/SidRichardsQuantum/Quantum_Error_Correction)
Explores the fundamentals of quantum error correction and early implementations of small error-correcting codes.
A growing project aligned with my long-term interest in fault-tolerant quantum computing.

---

## 🎓 Background
**MSci Theoretical Physics & Mathematics** (First Class) – Lancaster University
Former Data Analyst with experience automating workflows, building analytical pipelines, and using data-driven insights for decision support.

---

## 📫 Contact
LinkedIn: [https://www.linkedin.com/in/sid-richards-21374b30b/](https://www.linkedin.com/in/sid-richards-21374b30b/)

---

## Support

If my projects help your research or work, consider sponsoring development.
GitHub Sponsors helps maintain documentation, examples, and new features.

Sponsor: [https://github.com/sponsors/SidRichardsQuantum](https://github.com/sponsors/SidRichardsQuantum)
