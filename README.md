<p align="center">
  <img src="![Uploading 7c66eeb3-659d-4701-97e3-8faa4e2e6a8b.png…]()
 " width="600">
</p>


A lightweight and modular Tetris RL playground with a custom environment and multiple tabular algorithms implemented from scratch.  
Designed mainly for learning, experiments, and small research demos.

---

## 🚀 Features

- Custom Tetris environment with configurable board size and gravity  
- Clear reward shaping for RL research (step penalty, line reward, game-over penalty)  
- Dynamic Programming: Value Iteration (VI) & Policy Iteration (PI)  
- Model-free RL: Monte Carlo, SARSA, Q-Learning (tabular)  
- Simple logging & plotting utilities for learning curves and comparisons  
- Suitable for experiments with different α, γ, ε and reward-shaping strategies  

---

## 📁 Repository Structure

```text
tetris_env.py                     # Simplified Tetris environment
value_iteration_policy_iteration.py  # Value Iteration & Policy Iteration
mc_sarsa_qlearning.py             # Monte Carlo, SARSA, Q-Learning

