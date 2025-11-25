<!-- Badges: -->

[![Python](https://img.shields.io/badge/Python-3.13.5-informational)](https://www.python.org/downloads/source/)
[![Qiskit](https://img.shields.io/badge/Qiskit-2.1.1-informational)](https://github.com/Qiskit/qiskit)
[![Contributions](https://img.shields.io/badge/contributions-welcome-orange?style=flat-square)](https://github.com/qucai-lab/qiskit/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/qucai-lab/qiskit/graphs/commit-activity)

<!-- Logo: -->
<div align="center">
  <a href="https://qucai-lab.github.io/">
    <img src="https://github.com/qucai-lab/qucai-lab.github.io/blob/main/assets/QuCAI-Lab.png" height="250" width="250" alt="Logo">
  </a>
</div>

<div align="center">
    <img src="https://github.com/camponogaraviera/logos/blob/main/assets/ibmq_ntu.png" height="300" width="300" alt="Logo">
    <img src="https://github.com/camponogaraviera/logos/blob/main/assets/most.png" height="300" width="300" alt="Logo">
</div>

<!-- Title -->
<div align="center">
  <h1><b> Applied Quantum Information, Computation, and Communication with Qiskit SDK V2.x </b></h1>
</div>
<br>

<!-- Dependencies -->

# Core Dependencies

<a href="https://www.python.org/" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/python.png" width="120"></a>
<a href="https://numpy.org/" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/numpy.svg" width="40"></a>
<a href="https://matplotlib.org" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/matplotlib.svg" width="145"></a>
<a href="https://scipy.org/" target="_blank" rel="noopener noreferrer"><img src="https://scipy.org/images/logo.svg" width="40"></a>
<a href="https://www.sympy.org/en/index.html" target="_blank" rel="noopener noreferrer"><img src="https://www.sympy.org/static/images/logo.png" width="60"></a>
<a href="https://pyscf.org/" target="_blank" rel="noopener noreferrer"><img src="https://pyscf.org/_static/logo-64x64.png" width="40"></a>
<a href="https://qiskit.org/" target="_blank" rel="noopener noreferrer">
  <span style="display:inline-block;">
    <picture>
      <!-- dark mode -->
      <source srcset="https://github.com/camponogaraviera/logos/blob/main/assets/qiskit_white.png" width="37" alt="Light Logo">
       <!-- light mode -->
      <img src="https://github.com/camponogaraviera/logos/blob/main/assets/qiskit_black.png" width="37" alt="Dark Logo">
    </picture>
  </span>
</a>
<br>

# Table of Contents

<details>
<summary>Tooling and Version Control</summary>

- Version Control:

  - [SemVer](https://github.com/camponogaraviera/nvm-npm-yarn?tab=readme-ov-file#semantic-versioning-semver)
  - [Git](https://github.com/camponogaraviera/linux-git-conda/blob/dev/github_essentials/README.md)

- Environment Management:
  - [Anaconda](https://github.com/camponogaraviera/linux-git-conda/blob/dev/conda_essentials/README.md)
  </details>

---

<details>
<summary>Linear Algebra</summary>

- [Complex Numbers](notebooks/algebra/complex_numbers.ipynb)

- [Dirac Notation](notebooks/algebra/dirac.ipynb)
- [Hilbert Space](notebooks/algebra/hilbert_space.ipynb)
- [Basis States](notebooks/algebra/basis.ipynb)

- [Inner and Outer Product](notebooks/algebra/inner_product.ipynb)
- [Kronecker Product](notebooks/algebra/kronecker_product.ipynb)

- [Completeness Relation](notebooks/algebra/completeness_relation.ipynb)
- [Linear Operator](notebooks/algebra/linear_operator.ipynb)
- [Hermitian Operator](notebooks/algebra/hermitian_operator.ipynb)
- [Positive Operator](notebooks/algebra/positive_operator.ipynb)

- [Pauli Group](notebooks/algebra/pauli_group.ipynb)
- [Clifford Group](notebooks/algebra/clifford_group.ipynb)

- [Spectral Decomposition](notebooks/algebra/spectral_decomposition.ipynb)

- [Trace Function](notebooks/algebra/trace_function.ipynb)
- [Partial Trace](notebooks/algebra/partial_trace.ipynb)

  - Definition
  - Applications
  - Examples
    - Reduced density matrix of a bipartite system
    - Outer product representation for bipartite states
    - Measurement in a bipartite system
  - Python Implementation

- [Useful Linear Algebra Identities](notebooks/algebra/linear_algebra_identities.ipynb)

</details>

---

<details>
<summary>Quantum Mechanics Fundamentals</summary>

- [The Postulates of Quantum Mechanics](notebooks/quantum_mechanics/postulates.ipynb)
  - Postulate 1 (State Space)
  - Postulate 2 (Evolution)
  - Postulate 3 (Measurement)
    - Projective measurement (a.k.a von Neumann measurement) and Born's rule
    - Expectation value
  - Postulate 4 (Composite State)
- [Evolution in Closed Quantum Systems](notebooks/quantum_mechanics/evol_in_close_qsystems.ipynb)
  - Wave Mechanics Formalism
  - Matrix Mechanics Formalism
    - Schrödinger Picture (S-P)
    - Heisenberg Picture (H-P)
  - Density Matrix Formalism

</details>

---

<details>
<summary>Qiskit SDK</summary>
  
- [Qiskit SDK Overview](notebooks/qiskit/qiskit_components.ipynb)

</details>

---

<details>
<summary>Quantum Information</summary>

- [Review on Statistics](notebooks/quantum_information/statistics.ipynb)
- [Quantum Superposition](notebooks/quantum_information/superposition.ipynb)
  - Introduction
  - Mathematical Representation
- [Multipartite States](notebooks/quantum_information/multipartite_states.ipynb)
  - Introduction
  - Qudit State
  - Qubit State
  - Qutrit State
  - Composite Systems with Separable States
    - $n$-Qudit State
    - 2-Qubit State
    - 2-Qutrit State
- [Density Operator Formalism](notebooks/quantum_information/dens_op_form.ipynb)
  - Definition
  - Properties
  - Bound for Purity
  - Spectral Decomposition
  - Python Implementation
- [Bloch Sphere](notebooks/quantum_information/bloch_sphere.ipynb)
  - Introduction
  - Statevector Approach
  - Density Operator Approach
  - Plotting Pure and Mixed States with Qiskit
  - Python Implementation
- Entanglement
  - [Introduction](notebooks/quantum_information/intro.ipynb)
  - [Multipartite Entangled States](notebooks/quantum_information/multipartite_ent_stat.ipynb)
    - Introduction
    - Separable vs Entangled States
    - Bipartite Maximally Entangled Qudit States
    - Pure Entangled States with Maximally Mixed Subsystems
  - [Bell States](notebooks/quantum_information/bell_states.ipynb)
    - The Four Maximally Entangled 2-Qubit States
    - Qiskit Implementation
      - Bell states
      - Global measurement
  - [EPR Paradox](notebooks/quantum_information/epr.ipynb)
  - [CHSH Inequality](notebooks/quantum_information/chsh.ipynb)
    - Introduction
    - CHSH Violation
  - [CHSH Game](notebooks/quantum_information/chsh_game.ipynb)
    - Theory
    - Qiskit Implementation
  - [Bell Measurement and Applications](notebooks/quantum_information/bell_meas.ipynb)
    - Definition
    - Qiskit Implementation
      - Bell states
      - Bell measurement
      - Bell measurement on $|\phi^+ \rangle$
      - Bell measurement on $|\phi^- \rangle$
      - Bell measurement on $|\psi^+ \rangle$
      - Bell measurement on $|\psi^- \rangle$
    - Application in Teleportation
    - Application in Superdense Coding
  - [GHZ State](notebooks/quantum_information/ghz.ipynb)
    - GHZ State
    - GHZ-like State
  - [Entanglement Swapping](notebooks/quantum_information/ent_swapping.ipynb)
  - [Entanglement Monogamy](notebooks/quantum_information/ent_monogamy.ipynb)
    - Contrast with the Multipartite GHZ Entangled State
    - Contrast with the Multipartite W Entangled State
    - Connection with the no-Cloning Theorem and QKD
- [Trace Distance](notebooks/quantum_information/trace_distance.ipynb)
- Noise
  - [Types of Noise](notebooks/quantum_information/types_of_noise.ipynb)
    - Projection Noise
    - Measurement Noise
    - Coherent Noise
    - Incoherent Noise
  - [Evolution in Open Quantum Systems](notebooks/quantum_information/evolution_in_open_quantum_systems.ipynb)
    - Unitary Representation
    - Stinespring Representation
    - Kraus Representation a.k.a Axiomatic Approach
    - Lindblad Master Equation Approach
  - [Quantum Channels](notebooks/quantum_information/quantum_channels.ipynb)
    - Coherent Error Channel
    - Depolarizing Error Channel
    - Amplitude-Damping Channel
    - Phase Damping Channel
    - Phase-Amplitude Damping Error Channel
    - Kraus Error Channel
  - [State Purification](notebooks/quantum_information/state_purification.ipynb)

</details>

---

<details>
<summary>Quantum Computing</summary>

- [Hardware Platforms](notebooks/quantum_computing/hardware.pdf)
  - Circuit-based Superconducting Quantum Processors
- Quantum Gates
  - [Single-Qubit Gates](notebooks/quantum_computing/single_qubit_gates.ipynb)
  - [Two-Qubit Gates](notebooks/quantum_computing/two_qubit_gates.ipynb)
  - [Multi-Qubit Gates](notebooks/quantum_computing/multi_qubit_gates.ipynb)
  - [Gate Decomposition](notebooks/quantum_computing/gate_decomposition.ipynb)
  - [Universal Gate Set](notebooks/quantum_computing/universal_gate_set.ipynb)
- Quantum Circuits
  - [Textbook Vs. Little-Endian Convention](notebooks/quantum_computing/conventions.ipynb)
  - [Measurement in a Different Basis](notebooks/quantum_computing/change_of_basis.ipynb)
  - [Qiskit Operations](notebooks/quantum_computing/qiskit_operations.ipynb)
  - [Gate and Circuit Identities 1](notebooks/quantum_computing/gate_circuit_identities.ipynb)
  - [Gate and Circuit Identities 2](notebooks/quantum_computing/qc_identities.pdf)
- [State Preparation](notebooks/quantum_computing/state_preparation.ipynb)
  - Introduction
  - Unitary Decomposition
  - Schmidt Decomposition
  - Qiskit Examples
- Algorithms
  - [Deutsch](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms/quantum-query-algorithms/deutsch-algorithm)
  - [Deutsch-Jozsa](https://quantum.cloud.ibm.com/learning/en/modules/computer-science/deutsch-jozsa)
  - [Grover's](notebooks/quantum_computing/grover.ipynb)
  - [Shor's](https://quantum.cloud.ibm.com/docs/en/tutorials/shors-algorithm)
  - [Trotterization](notebooks/quantum_computing/trotterization.ipynb)
  - [Variational Quantum Eigensolver](notebooks/quantum_computing/vqe.ipynb)
  - [Sampling Quantum Diagonalization (SQD)](notebooks/quantum_computing/sqd.ipynb)
- Quantum Machine Learning
  - [Quantum Support Vector Machine](notebooks/quantum_computing/qsvm.ipynb)
  - [Quantum Kernel Alignment](notebooks/quantum_computing/qka.ipynb)
- Noise Reduction
  - [Simulating Circuits with Noise Channels](notebooks/quantum_computing/noisy_circuits.ipynb)
  - [Error Mitigation](notebooks/quantum_computing/error_mitigation.ipynb)

</details>

---

<details>
<summary>Quantum Communication</summary>
  
- Protocols
  - [Quantum Teleportation](notebooks/quantum_communication/teleportation.ipynb)
  - [Superdense Coding](notebooks/quantum_communication/superdense_coding.ipynb)
  - [BB84](notebooks/quantum_communication/bb84.ipynb)
  - [Ekert 91](notebooks/quantum_communication/ekert91.ipynb)
  - [DI-QKD vs MDI-QKD](notebooks/quantum_communication/di_vs_mdi.ipynb)
    
</details>

---

<details>
<summary>Interview Questions</summary>
  
- [Glossary](notebooks/interview_questions/glossary.ipynb)
- [Quantum Computation and Information](notebooks/interview_questions/README.md)
  
</details>

# Installs

1. Clone this repository and access the cloned directory:

```bash
git clone https://github.com/qucai-lab/qc-qiskit.git && cd qc-qiskit
```

2. Create the conda environment with required dependencies:

```bash
conda env create -f environment.yml && conda activate qc-qiskit
```

# Acknowledgement

This work was sponsored by the [IBMQ Hub at NTU](https://quantum.ntu.edu.tw/).

# Contributors

- [Lucas Camponogara Viera](https://www.github.com/camponogaraviera)

# References

[1] Nielsen MA, Chuang IL. 2010. "Quantum Computation and Quantum Information." New York: [Cambridge Univ. Press.](https://doi.org/10.1017/CBO9780511976667) 10th Anniv. Ed.

[2] [IBM Quantum Learning](https://learning.quantum.ibm.com/)

[3] [Qiskit Documentation](https://docs.quantum.ibm.com/)

[4] [Qiskit v2.0 Migration Guide](https://quantum.cloud.ibm.com/docs/en/migration-guides/qiskit-2.0)

[5] [IBM Quantum Platform](https://quantum.cloud.ibm.com/)

Complementary materials:

- [Upcoming and past events](https://www.ibm.com/quantum/events)
- [Qiskit Global Summer School (QGSS) 2025](https://github.com/qiskit-community/qgss-2025/tree/main)

# License

This work is licensed under a [Creative Commons Zero v1.0 Universal](LICENSE.md) license.
