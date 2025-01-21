# Quantum Speech Representation - QPAM

## Overview

This repository implements Quantum Probability Amplitude Modulation (QPAM) for representing audio signals using quantum computing principles. The method leverages the probabilistic nature of quantum mechanics to encode audio amplitudes as quantum probability amplitudes, enabling audio representation and retrieval through quantum circuits.

The implementation uses Qiskit, a quantum computing framework, to build quantum circuits and simulate the encoding and measurement process of audio signals.

## Features

- **Quantum Circuit Simulation**: Utilizes Qiskit Aer Simulator to simulate quantum circuits.
- **Audio Signal Representation**: Encodes real-valued audio signals as quantum probability amplitudes.
- **Reconstruction of Audio**: Measures the quantum state and reconstructs the audio signal from the measurement outcomes.
- **Audio Visualization**: Plots the original and reconstructed audio for comparison.

## Prerequisites

- Python 3.8 or higher
- Qiskit
- NumPy
- SciPy
- librosa
- matplotlib
- sounddevice
- scipy

Install required packages with the following command:

```bash
pip install qiskit numpy scipy librosa matplotlib sounddevice
```
[Link Text](URL)
