# Free-Energy Principle

A simple computational implementation of Karl Friston's
Free-Energy Principle.

## Overview

This project demonstrates the main computational ideas behind
the Free-Energy Principle, including:

- Generative models
- Prior beliefs
- Likelihood
- Posterior beliefs
- Prediction errors
- Precision
- Variational free energy
- Free-energy minimization
- Active inference

## Implementation

The implementation uses a simple Gaussian generative model.
The agent receives noisy sensory observations and tries to infer
the hidden state.

The notebook also demonstrates active inference, where actions
change the state of the environment to reduce prediction error.

## Requirements

```bash
pip install -r requirements.txt
