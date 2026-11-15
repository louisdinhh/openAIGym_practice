# Learning Reinforcement Learning with Gymnasium

## Overview

This repository contains three small projects developed while learning **Reinforcement Learning (RL)** using Python and OpenAI Gymnasium.

The projects explore how AI agents interact with simulated environments, learn from rewards, and improve their decision-making through trial and error.

I experimented with two reinforcement learning algorithms:
- **Deep Q-Network (DQN)**
- **Proximal Policy Optimization (PPO)**

## Projects

### 1. CartPole
- Environment: `CartPole-v1`
- Algorithm: DQN
- Objective: Train an agent to balance a pole by controlling a moving cart.
- Concepts: Experience replay, epsilon-greedy exploration, neural networks.

### 2. Atari Breakout
- Environment: Atari Breakout
- Algorithm: DQN
- Objective: Train an agent to play Breakout by controlling the paddle and destroying bricks.
- Concepts: State observations, action selection, reward optimisation.

### 3. BipedalWalker
- Environment: `BipedalWalker-v3`
- Algorithm: PPO
- Objective: Train a simulated bipedal robot to walk across uneven terrain.
- Concepts: Continuous control, policy optimisation, physics simulation.

## Technologies

- Python
- OpenAI Gymnasium
- PyTorch
- NumPy
- Matplotlib
- Box2D

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
