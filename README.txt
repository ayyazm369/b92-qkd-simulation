# B92 Quantum Key Distribution Simulation

This repository contains a simulation of the B92 Quantum Key Distribution (QKD) protocol using polarized laser pulses.

## Overview

The B92 protocol uses two non-orthogonal polarization states to encode quantum bits. This simulation models:

- Polarized photon state preparation
- Random measurement basis selection
- Conclusive and inconclusive detection events
- Quantum Bit Error Rate (QBER) calculation
- Optional intercept-resend eavesdropping attack

## Physics Model

States used:
- |0°⟩ (Horizontal polarization)
- |45°⟩ (Diagonal polarization)

Measurements:
- 90° (Vertical)
- 135° (Anti-diagonal)

The detection probability is computed using:

P = |⟨ψ_measurement | ψ_state⟩|²

## Features

- QBER estimation
- Sifted key generation
- Eavesdropping simulation (intercept-resend)

## Requirements

Install dependencies using:

pip install -r requirements.txt

## Author

Muhammad Ayyaz  
Physics Researcher | Quantum Information
