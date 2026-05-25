Research Protocol — 24.05.2026

# Description

A quantum-mechanical simulation was performed to generate an entangled two-qubit state representing a simplified model of quantum superposition and quantum correlation.

First, a Hadamard gate was applied to create a superposition state.  
Afterwards, a controlled-NOT (CNOT) gate was used to generate quantum entanglement between both qubits.

The resulting state corresponds to a Bell state.

---

# What was generated in the simulation?

A quantum-mechanical Bell state was generated in which both qubits can no longer be described independently, but instead form a shared quantum wavefunction.

---

# Which simulator was used?

Qiskit AerSimulator

---

# Result

The simulation predominantly produced the states:

| State | Meaning |
|-------|----------|
| 00 | both qubits measured as 0 |
| 11 | both qubits measured as 1 |

The states:

- 01
- 10

occurred ideally only extremely rarely or not at all.

This behavior reflects the correlated nature of the entangled quantum state.

---

# Interpretation of the Result

The simulation demonstrates that superposition and controlled entanglement can generate a non-separable quantum state whose statistical measurement outcomes correspond to the theoretical predictions of the quantum wavefunction.

The result confirms the mathematical description of entangled quantum systems through a shared wavefunction.

The measurements show that both qubits exhibit correlated states, although no definite classical values exist before measurement.

This demonstrates:

- quantum superposition
- quantum state correlation
- probabilistic interpretation of the wavefunction
- collapse of the quantum state during measurement

The simulation therefore represents a fundamental model of quantum-mechanical correlation processes that are conceptually related to molecular bonding phenomena in quantum chemistry.