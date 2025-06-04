# RALF: Robotic Autonomous Laundry Folder

## Overview

RALF (Robotic Autonomous Laundry Folder) is an AI-driven project focused on automating the task of folding laundry using computer vision and reinforcement learning. The repository contains modular Python scripts for two main components:

1. **Clothing Keypoint Detection**: Leverages deep learning (MaxViT-Unet backbone) to identify keypoints on garments, enabling precise robotic manipulation.
2. **Reinforcement Learning for Motion Planning**: Trains agents using state-of-the-art RL algorithms to perform complex tasks such as reaching, picking, and folding laundry items in simulation.

## Features

- **Keypoint Detection**: Utilizes MaxViT-Unet for accurate localization of garment features.
- **Advanced Reinforcement Learning**: Integrates Advantage Actor-Critic (A2C) and Truncated Quantile Critics (TQC) for robust policy learning.
- **Simulation with PandaGym**: Supports simulated robotic environments for safe and repeatable training.
- **Modular Codebase**: Easily extensible for new algorithms, simulation setups, or real-world hardware integration.
- **Reproducible Training**: Scripts and configuration files for replicable experiments and benchmarking.

## Requirements

- Python 3.8 or higher
- `keypoint-detection` library
- `PandaGym`
- `rl-baselines3-zoo`
- `stable-baselines3` and `sb3-contrib` (if not installed via zoo requirements)

## Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/metyu-melkonyan/RALF_Robotic_Laundry_Folder.git
cd RALF_Robotic_Laundry_Folder
pip install -r requirements.txt
```

## Getting Started

1. **Keypoint Detection**  
   Run scripts in the `keypoint_detection/` directory to train or test the MaxViT-Unet model on clothing images.
2. **Reinforcement Learning**  
   Use the scripts in `rl/` to launch motion planning experiments in PandaGym environments with your preferred RL algorithm.

## References

- [RL Baselines3 Zoo](https://github.com/rl-baselines3-zoo)
- [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3)
- [SB3 Contrib](https://github.com/Stable-Baselines3-contrib)
- [Panda Gym Environments Paper](https://arxiv.org/abs/2004.07474)

For more details, see the [tqc-PandaReach-v1 model page](https://example.com).

---

Feel free to open issues or pull requests for suggestions and improvements.
