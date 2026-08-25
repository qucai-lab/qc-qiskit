<!-- Logos -->

<a href="https://www.python.org/" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/python.png" width="120"></a>
<a href="https://numpy.org/" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/numpy.svg" width="40"></a>
<a href="https://matplotlib.org" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/matplotlib.svg" width="145"></a>
<a href="https://scipy.org/" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/scipy.png" width="40"></a>
<a href="https://www.sympy.org/en/index.html" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/sympy.png" width="60"></a>
<a href="https://pyscf.org/" target="_blank" rel="noopener noreferrer"><img src="https://github.com/camponogaraviera/logos/blob/main/assets/pyscf.png" width="40"></a>
<a href="https://qiskit.org/" target="_blank" rel="noopener noreferrer"></a>

<a href="https://qiskit.org/" target="_blank" rel="noopener noreferrer">
<picture>
<!-- dark mode -->
<source srcset="https://github.com/camponogaraviera/logos/blob/main/assets/qiskit_white.png" width="40" alt="Light Logo">
<!-- light mode -->
<img src="https://github.com/camponogaraviera/logos/blob/main/assets/qiskit_black.png" width="40" alt="Dark Logo">
</picture>
</a>
<br>

&nbsp;

<!-- Badges -->

[![Python](https://img.shields.io/badge/Python-3.11.0-informational)](https://www.python.org/downloads/source/)
[![Qiskit](https://img.shields.io/badge/Qiskit-2.2.3-informational)](https://github.com/Qiskit/qiskit)
[![Contributions](https://img.shields.io/badge/contributions-welcome-orange?style=flat-square)](https://github.com/qucai-lab/qiskit/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/qucai-lab/qiskit/graphs/commit-activity)

<!-- Logo: -->
<div align="center">
  <a href="https://qucai-lab.github.io/">
    <img src="https://github.com/qucai-lab/qucai-lab.github.io/blob/main/assets/QuCAI-Lab.png" height="250" width="250" alt="Logo">
  </a>
</div>

<!-- Title -->
<div align="center">
  <h1><b> Applied Quantum Information, Computation, and Communication with Qiskit SDK V2.x </b></h1>
</div>
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

- [Complex Analysis](notebooks/algebra/complex_analysis.ipynb)
  - Complex Numbers
  - Complex Functions
  - Complex Plane

- [Dirac Notation](notebooks/algebra/dirac.ipynb)

- [Vector Space](notebooks/algebra/vector_space.ipynb)
  - Definition
  - Linear Independence

- [Inner Product](notebooks/algebra/inner_product.ipynb)
  - Definition
  - Properties
  - Applications
  - Examples
    - Standard Inner Product of Vectors
    - Hilbert-Schmidt Inner Product
  - Python Implementation

- [Kronecker Product](notebooks/algebra/kronecker_product.ipynb)
  - Definition
  - Properties
  - Applications
  - Examples
  - Python Implementation

- [Hilbert Space](notebooks/algebra/hilbert_space.ipynb)
  - Definition
  - Composite Spaces

- [Basis States](notebooks/algebra/basis.ipynb)
  - $Z$-basis
  - $X$-basis
  - $Y$-basis
  - $H$-basis
  - Bell-basis

- [Unitary Operators](notebooks/algebra/unitary_operator.ipynb)
  - Definition
  - Examples

- [Normal Operators](notebooks/algebra/normal_operator.ipynb)
  - Definition
  - Examples

- [Linear Operators](notebooks/algebra/linear_operator.ipynb)
  - Definition
  - Matrix Representation for Linear Operators
  - Properties
  - Applications
  - Examples

- [Hermitian Operators](notebooks/algebra/hermitian_operator.ipynb)
  - Definition
  - Properties
  - Applications

- [Positive Operators](notebooks/algebra/positive_operator.ipynb)
  - Definition
  - Properties
  - Applications

- [Outer Product](notebooks/algebra/outer_product.ipynb)
  - Definition
  - Applications
  - Examples
  - Python Implementation

- [Spectral Decomposition](notebooks/algebra/spectral_decomposition.ipynb)
  - Definition
  - Examples

- [Operator and Matrix functions](notebooks/algebra/operator_matrix_functions.ipynb)
  - Operator Function
    - Definition
    - Examples
      - SQRT(A)
      - ln(A)
      - exp(A)
        - Gibbs Thermal State
      - Zassenhaus Formula
      - Trotter-Suzuki Formula
  - Matrix Function
    - Baker-Campbell-Hausdorff Formula

- [Completeness Relation](notebooks/algebra/completeness_relation.ipynb)
  - Definition
  - Applications

- [Commutator and Anticommutator](notebooks/algebra/commutator_anticommutator.ipynb)
  - Definition
  - Theorem
  - Properties
  - Applications
  - Examples

- [Trace Function](notebooks/algebra/trace_function.ipynb)
  - Definition

- [Partial Trace](notebooks/algebra/partial_trace.ipynb)
  - Definition
  - Applications
  - Examples
    - Reduced Density Matrix of a Bipartite System
    - Measurement in a Bipartite System
  - Python Implementation

- [Schmidt Decomposition](notebooks/algebra/schmidt_decomposition.ipynb)
  - Introduction
  - Applications

- [Pauli Group](notebooks/algebra/pauli_group.ipynb)
  - Pauli Matrices
  - Pauli Algebra
  - Pauli Group

- [Clifford Group](notebooks/algebra/clifford_group.ipynb)
  - Clifford Group
  - Clifford Gates

- [Useful Linear Algebra Identities](notebooks/algebra/linear_algebra_identities.ipynb)

</details>

---

<details>
<summary>Quantum Mechanics Fundamentals</summary>

- [The Postulates of Quantum Mechanics](notebooks/quantum_mechanics/postulates.ipynb)
  - Introduction
  - State Postulate
    - State Vector
      - Discrete Spectrum
      - Continuous Spectrum
    - Composite Systems
  - Observable Postulate
  - Time Evolution Postulate
  - Measurement Postulate
    - General Description for Measurements
    - Positive Operator-Valued Measure (POVM)
    - Projective measurement (a.k.a von Neumann measurement) and Born's rule
      - Discrete Spectrum
      - Continuous Spectrum
    - Expectation value
    - Examples

- [Evolution in Closed Quantum Systems](notebooks/quantum_mechanics/evol_in_close_qsystems.ipynb)
  - Wave Mechanics Formalism
  - Matrix Mechanics Formalism
    - Schrödinger Picture (S-P)
    - Heisenberg Picture (H-P)
    - Solution for the Schrödinger Equation
  - Density Matrix Formalism

</details>

---

<details>
<summary>Qiskit SDK</summary>
  
- [Qiskit SDK Overview](notebooks/qiskit/qiskit_components.ipynb)

- [Qiskit Operations](notebooks/qiskit/qiskit_operations.ipynb)
  - Measurement Operation
  - Reset Operation
  - Barrier Operation
  - Delay Operation

</details>

---

<details>
<summary>Quantum Information</summary>

- [Quantum Superposition](notebooks/quantum_information/superposition.ipynb)
  - Introduction
  - Mathematical Representation
  - Qiskit Example

- [Multipartite Separable States](notebooks/quantum_information/multipartite_states.ipynb)
  - Introduction
  - Qudit State
  - Qubit State
  - Qutrit State
  - Composite Systems with Separable States
    - $n$-Qudit State
    - 2-Qudit State
    - 2-Qubit State
    - 2-Qutrit State

- [Density Operator Formalism](notebooks/quantum_information/dens_op_form.ipynb)
  - Definition
  - Properties
  - Bound for Purity
  - Spectral Decomposition
  - Bipartite Systems
  - Python Implementation

- [Bloch Sphere](notebooks/quantum_information/bloch_sphere.ipynb)
  - Introduction
  - Statevector Approach
  - Density Operator Approach
  - Plotting Pure and Mixed States with Qiskit
  - Python Implementation

- [State Purification](notebooks/quantum_information/state_purification.ipynb)

- [State Preparation](notebooks/quantum_information/state_preparation.ipynb)
  - Introduction
  - Unitary Decomposition
  - Qiskit Examples

- Entanglement
  - [Introduction](notebooks/quantum_information/entanglement/intro.ipynb)
  - [Multipartite Entangled States](notebooks/quantum_information/entanglement/multipartite_ent_stat.ipynb)
    - Introduction
    - Separable vs Entangled States
    - Bipartite Maximally Entangled Qudit States
    - Pure Entangled States with Maximally Mixed Subsystems
  - [Bell States](notebooks/quantum_information/entanglement/bell_states.ipynb)
    - The Four Maximally Entangled 2-Qubit States
    - Qiskit Implementation
      - Bell states
      - Global measurement
  - [GHZ State](notebooks/quantum_information/entanglement/ghz.ipynb)
    - The Maximally Entangled $n$-Qudit GHZ State
    - Particular Cases with Qiskit
      - $n$-qubit
      - $3$-qubit
      - $n$-qutrit
    - GHZ-like State
  - [EPR Paradox](notebooks/quantum_information/entanglement/epr.ipynb)
    - EPR Hypothesis
    - EPR Argument
  - [CHSH Inequality](notebooks/quantum_information/entanglement/chsh.ipynb)
    - Introduction
    - CHSH Violation
  - [CHSH Game](notebooks/quantum_information/entanglement/chsh_game.ipynb)
    - Theory
    - Qiskit Implementation
  - [Bell Measurement and Applications](notebooks/quantum_information/entanglement/bell_meas.ipynb)
    - Definition
    - Qiskit Implementation
      - Bell states
      - Bell measurement
      - Bell measurement on $|\phi^+ \rangle$
      - Bell measurement on $|\phi^- \rangle$
      - Bell measurement on $|\psi^+ \rangle$
      - Bell measurement on $|\psi^- \rangle$
    - Applications
      - Entanglement Swapping
      - Quantum Teleportation
      - Superdense Coding
  - [Entanglement Swapping](notebooks/quantum_information/entanglement/ent_swapping.ipynb)
  - [Entanglement Monogamy](notebooks/quantum_information/entanglement/ent_monogamy.ipynb)
    - Definition
    - Does the GHZ State Violate Monogamy?

- Distance Measurements
  - [P-norm Distance](notebooks/quantum_information/distance_measurements/pnorm_distance.ipynb)
    - P-norm Distance
    - Trace Distance
    - Hilbert-Schmidt Distance
    - Implementation

  - [State Fidelity](notebooks/quantum_information/distance_measurements/state_fidelity.ipynb)
    - Definition
    - Implementation

- Noise
  - [Types of Noise](notebooks/quantum_information/noise/types_of_noise.ipynb)
    - Projection Noise
    - Measurement Noise
    - Coherent Noise
    - Incoherent Noise
  - [Evolution in Open Quantum Systems](notebooks/quantum_information/noise/evolution_in_open_quantum_systems.ipynb)
    - Unitary Representation
    - Stinespring Representation
    - Kraus Representation a.k.a Axiomatic Approach
    - Lindblad Master Equation Approach
  - [Quantum Channels](notebooks/quantum_information/noise/quantum_channels.ipynb)
    - Coherent Error Channel
    - Depolarizing Error Channel
    - Amplitude-Damping Channel
    - Phase Damping Channel
    - Phase-Amplitude Damping Error Channel
    - Kraus Error Channel

</details>

---

<details>
<summary>Quantum Computing</summary>

- [Review on Statistics](notebooks/quantum_computing/statistics.ipynb)

- Quantum Gates
  - [Introduction](notebooks/quantum_computing/quantum_gates/gates.ipynb)
  - [Textbook Vs. Little-Endian Convention](notebooks/quantum_computing/quantum_gates/conventions.ipynb)
  - [Single-Qubit Gates](notebooks/quantum_computing/quantum_gates/single_qubit_gates.ipynb)
  - [Two-Qubit Gates](notebooks/quantum_computing/quantum_gates/two_qubit_gates.ipynb)
  - [Multi-Qubit Gates](notebooks/quantum_computing/quantum_gates/multi_qubit_gates.ipynb)
  - [Universal Gate Set](notebooks/quantum_computing/quantum_gates/universal_gate_set.ipynb)
  - [Implementations](notebooks/quantum_computing/quantum_gates/implementations.ipynb)

- Operator Decompositions
  - Additive-based decompositions
    - [Pauli Decomposition](notebooks/quantum_computing/operator_decomposition/pauli_decomposition.ipynb)
    - [Operator Schmidt Decomposition](notebooks/quantum_computing/operator_decomposition/operator_schmidt_decomposition.ipynb)
    - [Linear Combination of Unitaries (LCU)](notebooks/quantum_computing/operator_decomposition/lcu.ipynb)
  - Product-based decompositions
    - [Euler Decomposition](notebooks/quantum_computing/gate_decompositions/euler_decomposition.ipynb)
      - Z-X-Z Decomposition
      - Z-Y-Z Decomposition
      - X-Y-X Decomposition
      - X-Z-X Decomposition
      - V-Z Decomposition

- [Unitary/Circuit Synthesis](notebooks/quantum_computing/circuit_synthesis/circuit_synthesis.ipynb)
  - Introduction
  - Controlled-unitary Decomposition
  - KAK Decomposition
  - Cosine-Sine Decomposition (CSD)
  - Quantum Shannon Decomposition (QSD)
  - Block ZXZ Decomposition

- Quantum Circuits
  - [Measurement in a Different Basis](notebooks/quantum_computing/quantum_circuits/change_of_basis.ipynb)
  - [Gate and Circuit Identities 1](notebooks/quantum_computing/quantum_circuits/gate_circuit_identities.ipynb)
  - [Gate and Circuit Identities 2](notebooks/quantum_computing/quantum_circuits/qc_identities.pdf)

- Classical Algorithms
  - [Density Matrix Renormalization Group (DMRG)](notebooks/quantum_computing/classical_algorithms/dmrg.ipynb)

- Quantum Algorithms
  - Deutsch
  - Deutsch-Jozsa
  - [Grover's](notebooks/quantum_computing/quantum_algorithms/grover.ipynb)
  - [Quantum phase estimation (QPE)](notebooks/quantum_computing/quantum_algorithms/qpe.ipynb)
  - Shor's
  - [Trotterization](notebooks/quantum_computing/quantum_algorithms/trotterization.ipynb)
  - [Variational Quantum Eigensolver (VQE)](notebooks/quantum_computing/quantum_algorithms/vqe.ipynb)
  - [ADAPT-VQE](notebooks/quantum_computing/quantum_algorithms/adapt_vqe.ipynb)

- [Error Mitigation](notebooks/quantum_computing/quantum_algorithms/error_mitigation.ipynb)

</details>

---

<details>
<summary>Quantum Communication and Cryptography</summary>
 
- Theorems
  - [No-communication Theorem](notebooks/quantum_communication/theorems/no_communication.ipynb)
  - [No-cloning Theorem](notebooks/quantum_communication/theorems/no_cloning.ipynb)
    - Theorem
    - Proof
    - Implications
    - Example

- Quantum Communication Protocols
  - [Quantum Teleportation](notebooks/quantum_communication/communication/teleportation.ipynb)
    - Theory
    - Applications
    - Qiskit Implementation
  - [Superdense Coding](notebooks/quantum_communication/communication/superdense_coding.ipynb)

- Quantum Cryptography Protocols
  - [BB84](notebooks/quantum_communication/cryptography/bb84.ipynb)
  - [Ekert 91](notebooks/quantum_communication/cryptography/ekert91.ipynb)

- Frameworks for QKD
  - [DI-QKD vs MDI-QKD](notebooks/quantum_communication/qkd/di_vs_mdi.ipynb)

</details>

---

<details>
<summary>Q&A</summary>
  
- [Q&A](notebooks/interview_questions/README.md)
  
</details>

# Conda Environment

```bash
conda env create -f environment.yml && conda activate qc-qiskit
```

# Acknowledgement

This work was sponsored by the [IBMQ Hub at NTU](https://quantum.ntu.edu.tw/).

<div align="center">
    <img src="https://github.com/camponogaraviera/logos/blob/main/assets/ibmq_ntu.png" height="300" width="300" alt="Logo">
</div>

# References

[1] Griffiths, D. J., &#38; Schroeter, D. F. (2018). Introduction to Quantum Mechanics (3rd ed.). Cambridge: Cambridge University Press. https://doi.org/10.1017/9781316995433

[2] Nielsen, M. A., &#38; Chuang, I. L. (2010). Quantum Computation and Quantum Information: 10th Anniversary Edition. Cambridge: Cambridge University Press. https://doi.org/10.1017/CBO9780511976667

[3] Wilde, M. M. (2017). Quantum Information Theory (2nd ed.). Cambridge: Cambridge University Press. https://doi.org/10.1017/9781316809976

[4] Wolf, R. (2021). Quantum key distribution: An introduction with exercises. Springer. https://doi.org/10.1007/978-3-030-73991-1

[5] [Qiskit documentation](https://docs.quantum.ibm.com/).

[6] [Qiskit v2.0 migration guide](https://quantum.cloud.ibm.com/docs/en/migration-guides/qiskit-2.0).

# License

This work is licensed under a [Creative Commons Zero v1.0 Universal](LICENSE.md) license.
