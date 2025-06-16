# Markov Decision Process (MDP) with Value Iteration

This repository contains an educational implementation of a **Markov Decision
Process (MDP)** in Python, along with value iteration to compute optimal
policies. It includes two example scenarios with graph visualizations and value
function calculations.

## Features

- General-purpose MDP class that supports:
    - Custom state/action/reward definitions
    - Probabilistic transitions
    - Terminal states
- Value Iteration algorithm implementation
- Automatic optimal policy extraction
- Matplotlib-based visualization of the state transition graph

## Example Scenarios

### 1. Home to Work Commute

You must decide how to commute from **HOME** to **WORK** by choosing among:

- 🚲 Bike (deterministic, 45 minutes)
- 🚗 Car (random traffic conditions)
- 🚉 Train (random delays and possible return to home)

The goal is to **minimize expected time**, so all rewards are **negative
durations**.

## Installation

```bash
git clone https://github.com/IvanDzanija/SSPA.git
uv sync
```

## Usage

Open in Jupyter notebook and have fun with it!
