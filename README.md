# RALF: Robotic Autonomous Laundry Folder
## Overview

RALF (Robotic Autonomous Laundry Folder) is a project designed to explore AI and robotics techniques for automating the task of folding laundry. This repository contains scripts for two main components of the project:

1. **Clothing Keypoint Detection**: Using AI-based methods to detect keypoints in clothing for precise manipulation.
2. **Reinforcement Learning for Motion Planning**: Training agents to perform tasks like reaching, picking, and placing laundry.

## Features
- Keypoint detection using the MaxViT-Unet backbone.
- Reinforcement learning with Advantage Actor-Critic (A2C) and Truncated Quantile Critics (TQC) algorithms.
- Simulation environments provided by PandaGym.

## Requirements
- Python 3.8 or higher
- `keypoint-detection` library
- `PandaGym`
- `rl-baselines3-zoo`

Install dependencies:
```bash
pip install -r requirements.txt
