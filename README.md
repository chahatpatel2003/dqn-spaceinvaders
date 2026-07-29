# DQN Space Invaders Agent

A reinforcement-learning project exploring how a Deep Q-Network learns to play Atari Space Invaders through reward-based interaction.

## Project Overview

This academic project adapted a Deep Q-Network workflow for the Space Invaders environment. The agent learned through repeated gameplay using reinforcement-learning techniques such as:

- Experience replay
- Epsilon-greedy exploration
- Reward-based policy learning
- Iterative policy optimization
- Neural-network action-value estimation

## Training Demonstration

### Early Training

The agent behaves mostly randomly, misses targets frequently, and loses lives quickly.

[View early training video](assets/early_training.mp4)

### Later Training

After additional training, the agent moves more purposefully, positions itself beneath enemies, and hits targets more consistently.

[View later training video](assets/later_training.mp4)

## Observations

The later gameplay demonstrates visible behavioral improvement compared with the initial policy. Longer training, slower epsilon decay, and a larger replay buffer could further improve stability and performance.

## Repository Structure

```text
.
├── assets/
│   ├── early_training.mp4
│   └── later_training.mp4
└── README.md
