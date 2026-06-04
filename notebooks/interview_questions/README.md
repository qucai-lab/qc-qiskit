<div align="center">
  <h1><b> Q&A </b></h1>
</div>

# Table of Contents

- [Quantum Information](quantum-information)
- [Quantum Computing](quantum-computing)

---

# Quantum Information

- **What is a qubit, and how is it different from a regular bit?**
  - Answer: A bit is the basic unit of information in regular computers, as it can be either 0 or 1. A qubit is the basic unit of information in quantum computers.

- **What is superposition in simple terms?**
  - Answer: Superposition allows a quantum system of $N$ qubits to exist in a linear combination of $2^N$ basis states at once before the system is measured. Through carefully designed quantum gates, the amplitudes of these states can be manipulated so that interference effects emerge. Constructive interference increases the probability of correct or desired outcomes, while destructive interference reduces the probability of incorrect ones.

- **What is entanglement in simple terms?**
  - Answer: Entanglement is a phenomenon in which multiple qubits become correlated in such a way that their joint state cannot be written as a tensor product of individual qubit states. This non-classical (quantum) correlation is a key resource in quantum computing, as it enables computational advantages that quantum algorithms can achieve over classical methods for certain classes of problems.

- **Q: "Why must all quantum observables be Hermitian?"**
  - Answer: Quantum observables are linear operators describing physical quantities and, therefore, they must have real eigenvalues $\lambda_j = \lambda_j^*$, hence they should be represented by Hermitian matrices. Within the matrix mechanics formalism of quantum mechanics, initially developed by Werner Heisenberg, Max Born, and Pascual Jordan, the physical observables (e.g., `hamiltonian`, `electric charge`, `magnetic flux`, `position`, `momentum`, etc.) are represented by self-adjoint (Hermitian) operators where the corresponding eigenvectors form a set of orthonormal basis for the Hilbert space.

- **Q: "Are all quantum observables represented by Unitary matrices?"**
  - Answer: no! This is not a requirement. Most observables are not unitary, including: position and momentum.

- **Q: "Are all quantum operations represented by Unitary matrices?"**
  - Answer: no! The measurement operation, the reset of qubits, and the classical conditional operations are non-unitary operations.

- **Q: "Are all quantum evolutions represented by Linear operators?"**
  - Answer: yes! Quantum Mechanics is a Linear theory! Even quantum channels are described by linear CPTP maps. In general, a CPTP map is a superoperator (an operator acting on another operator).

- **Q: "Are all quantum evolutions represented by Unitary operators?"**
  - Answer: no! In open quantum systems, the dynamics (evolution) under a quantum channel can be represented by a Unitary operation acting on the global mixed¹ state of the composite Hilbert space (system of interest² + environment). However, the evolution of the system of interest, treated in isolation after tracing out the environment, is described by a non-unitary operation. The reason is that, via system-environment interactions, the environment will couple with the system creating correlations in such a way that it causes decoherence (a non-unitary process) in the system of interest, and sometimes entanglement³ between the two subsystems.

<br>

---

¹In noisy quantum systems, incoherent noise creates a mixed state, i.e, a probability distribution over pure states. Although a mixed state (see Ref. [1]) consists of an ensemble (statistical mixture) of $N$ pure states ($\{p_j, |\psi_j\rangle\}_{j=1}^n$), a mixed state cannot be represented by a linear combination of the aforementioned normalized state vectors (pure states) that are defined on a separable Hilbert Space. Therefore, the evolved mixed state must be represented by a mixed density operator rather than a statevector. Recall that coherent noise is described by unitary operations, while incoherent noise generates mixed states that are always random, regardless of the basis in which they are measured.

²An open quantum system can be divided into two subsystems: the system of interest and the environment. The system of interest can be isolated after tracing out the environment from the global state of the system.

³Consider a system of interest interacting with the environment. It is possible to create entanglement even if the two systems are initially uncorrelated, but there must be coherence in one of them. One prime example is a system of interest initially in a coherent state (e.g., 1-qubit state) and the environment in a classical state (e.g., $|0\rangle$).

---

# Quantum Computing

- **What is quantum computing?**
  - Answer: Quantum computing is a new computing paradigm that leverages the principles of quantum mechanics. Instead of using regular bits (which are either 0 or 1), it uses qubits in superposition. This allows quantum computers to perform certain calculations in polynomial time compared to classical computers.

- **What can quantum computers do better than regular (classical) computers?**
  - Answer: Quantum computers are good at solving specific types of problems that either require simulating quantum systems or involve complex calculations. Examples: finding the ground state of large molecules (VQE, SQD), factoring prime numbers (QFT with Shor’s algorithm), searching unstructured data (Grover’s algorithm), and finding approximate solutions for NP-hard problems such as the traveling salesman and Max-Cut (QAOA).

- **Will quantum computers replace regular (classical) computers?**
  - Answer: No! Quantum computers are very powerful for specific types of problems, but regular computers are still better for everyday tasks like arithmetic, gaming, browsing, or watching videos.

- **Does increasing the number of qubits in the system speed up the computation (decrease time complexity)?**
  - Answer: No! Exponential speedup (polynomial time) and quantum advantage arise from the principle of quantum interference, which is often enabled by entanglement.

- **Does a real quantum computer executes matrix multiplications?**
  - Answser: A real quantum computer doesn't numerically compute matrix multiplications like a classical computer. But mathematically, its operations are equivalent to multiplying state vectors by unitary matrices. On a real quantum device, you get the same outcome "for free" because nature carries out the unitary evolution directly.

- **Q: "Are all quantum gates represented by Linear operators?"**
  - Answer: yes! In close quantum systems, quantum gates perform quantum evolutions described by the Schrödinger equation that is a differential equation over a linear operator $\hat{U}$:

\begin{equation}
i\hbar \frac{d}{dt}(\hat{U}(t) |\psi_0\rangle)=\hat{H}(\hat{U}(t) |\psi_0\rangle).
\end{equation}

- **Q: "Are all quantum gates represented by Unitary matrices?"**
  - Answer: in closed quantum systems, yes! In open quantum systems, the evolution of the system alone is generally described by a non-unitary quantum channel, even though the global mixed state (system + environment) evolves unitarily.
  - Unitary matrices have the property to preserve the inner product between two arbitrary states. Hence, the norm of a state is also preserved and, consequently, the probability amplitude of all possible measurement outcomes:

  $$\langle \psi_i|\hat{U}^{\dagger} \hat{U} |\psi_j\rangle = \langle \psi_i|\psi_j\rangle. \\ \text{(Preserve the inner product)}$$

<br>

$$\langle \psi|\hat{U}^{\dagger} \hat{U} |\psi\rangle = \langle \psi |\psi\rangle=|\psi|^2=\Bigg(\sum_{j=1}^{d=2^n}c_j|o_j\rangle \Bigg)^{\dagger}\Bigg(\sum_{k=1}^{d=2^n} c_k |o_k\rangle \Bigg)=\sum_{j,k=1}^{d=2^n} c_j^* c_k \langle o_j|o_k\rangle= \sum_{j,k=1}^{d=2^n} c_j^* c_k \delta_{jk} = \sum_{j=1}^{d=2^n}|c_j|^2=\sum_{j=1}^{d=2^n}Pr(o_j|\psi\rangle)=1. \\ \text{(Preserve the norm)}$$

- **Q: "Are all quantum gates represented by Hermitian matrices?"**
  - Answer: no! Examples of non-Hermitian quantum gates are: the `phase gate T`, and the `phase gate S`.

- **Q: "Are all quantum gates reversible?"**
  - Answer: yes! This is a consequence of the linearity of quantum mechanics, since quantum gates are represented by Unitary operators with the property $\hat{U}\hat{U}^{\dagger}=\hat{U}\hat{U}^{-1}=\mathbb{I}$ which ca be used to undone their action.
