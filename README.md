DONT HAVE TIME TO READ THE WHOLE README.MD!!!! IN SIMPLE:

This project is about training an AI agent to play the Google Chrome Dino game using Deep Reinforcement Learning (DQN).

Instead of manually programming when the Dino should jump or avoid obstacles, I trained an agent to learn through trial and error. It observes the game, takes actions, receives rewards or penalties, and gradually learns how to survive longer.

In short: Teaching an AI to play the Dino game using its own experience rather than predefined instructions.

---Reinforcement Learning:

*DQN — Learns the best actions using a neural network.

*Experience Replay — Stores and reuses previous experiences.

*Target Network — Helps stabilize the learning process.

*Epsilon-Greedy — Balances exploration and exploitation.

*Reward-Based Learning — Improves decisions through rewards and penalties.

---Tech Stack---

Python · PyTorch · NumPy · Jupyter Notebook

---NOW THE DETAILS PART---

Project Overview

The project uses Deep Q-Network (DQN), a reinforcement learning algorithm that combines Q-Learning with deep neural networks.

The agent interacts with the Dino game environment and learns which actions produce better long-term rewards. With repeated training, it gradually improves its ability to avoid obstacles and survive longer.

How It Works

The agent observes the current game state.

It selects an action, such as jumping or doing nothing.

The environment returns a reward and the next state.

The experience is stored in the Replay Buffer.

The agent samples previous experiences to train its neural network.

The network updates its Q-value predictions using the Bellman equation.

The process repeats, allowing the agent to improve over time.
