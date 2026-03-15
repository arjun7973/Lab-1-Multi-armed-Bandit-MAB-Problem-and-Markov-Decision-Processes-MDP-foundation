# Lab 1 - Reinforcement Learning 

Multi-Armed Bandit Problem and MDP Foundations 

## Overview
This project contains two parts:

1. **Multi-Armed Bandit Experiment**
   - Custom 10-armed bandit environment with Gaussian distribution rewards.
   - Implements **ε-greedy** and **UCB** agent algorithms.
   - Evaluates agents over **2000 steps and 1000 runs**.
   - Plots metrics' evaluation: average reward and optimal action percentage.

2. **Gymnasium Environment Exploration**
   - Inspects **FrozenLake-v1** and **Taxi-v3** environments.
   - Implemented and evaluates a **Random Policy Agent** for **FrozenLake-v1** and **Taxi-v3** environments.

---

## Setup

1. Install dependencies:

```python
%pip install numpy matplotlib gymnasium
```

2. Load Libraries

```python
import numpy as np
import matplotlib.pyplot as plt
import gymnasium as gym
```
