Research Protocol — 24.05.2026

# Description

A quantum-mechanical entanglement experiment was executed on real IBM Quantum hardware using a two-qubit Bell-state circuit.

The objective of the experiment was to compare ideal quantum simulation results with measurements obtained from a physical quantum processor affected by real hardware noise, decoherence, and gate imperfections.

The experiment used a Hadamard gate to generate quantum superposition followed by a controlled-NOT (CNOT) gate to produce quantum entanglement between two qubits.

---

# Objective of the Experiment

The goal of the experiment was to investigate how real quantum hardware behaves compared to an idealized simulator environment.

Particular focus was placed on:

- quantum superposition
- entanglement generation
- measurement probabilities
- hardware-induced deviations
- decoherence effects

---

# Quantum Backend Used

IBM Quantum Backend:
ibm_kingston

Framework:
Qiskit Runtime + SamplerV2

Shots:
2048

---

# Quantum Circuit

The circuit consisted of:

1. Hadamard gate (H)
2. Controlled-NOT gate (CNOT)
3. Measurement of both qubits

This circuit generates a Bell state:

|Φ⁺⟩ = (|00⟩ + |11⟩) / √2

---

# Result

The dominant measured states were:

- 00
- 11

Additional lower-probability states were also observed:

- 01
- 10

Unlike the ideal simulator, real hardware introduced deviations caused by physical quantum noise.

---

# Interpretation of the Result

The experiment confirms that real quantum hardware can successfully generate entangled quantum states whose dominant measurement probabilities follow the theoretical Bell-state prediction.

However, unlike the ideal simulation, additional non-ideal states appeared due to physical limitations of the quantum processor.

These deviations originate from:

- decoherence
- gate errors
- readout noise
- thermal fluctuations
- qubit instability

The experiment therefore demonstrates both:

1. successful generation of quantum entanglement
2. the practical limitations of current noisy intermediate-scale quantum (NISQ) hardware

The results illustrate the difference between ideal mathematical quantum systems and physically implemented quantum computation.

This experiment also demonstrates how probabilistic quantum behavior becomes experimentally observable on real hardware systems.