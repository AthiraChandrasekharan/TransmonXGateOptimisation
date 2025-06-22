# Transmon Gate Optimization via Jaynes–Cummings Model

This project investigates **gate optimization** for **transmon qubits** using the **Jaynes–Cummings model** as a simplified yet insightful framework. The goal is to improve the performance of quantum gates implemented in transmon–cavity systems.

---

## Overview

Transmon qubits are a leading platform for superconducting quantum computing. Gate operations often involve controlled interactions with a resonator or cavity. This project uses the **Jaynes–Cummings Hamiltonian** to model such interactions and study
dynamics during gate operations

---

## Methodology

We use the Jaynes–Cummings Hamiltonian:

$$
H = \omega_c a^\dagger a + \omega_a \sigma^\dagger \sigma + g(a^\dagger \sigma + a \sigma^\dagger)
$$

and extend it to simulate gate dynamics
Simulations are carried out using `QuTiP`.

---


## Requirements

- Python ≥ 3.8
- QuTiP
- NumPy
- Matplotlib


