# CartPoleSolution
# Reinforcement Learning with DQN

This repository contains the code for training and using a Deep Q-Network (DQN) agent to solve a reinforcement learning task using the OpenAI Gym environment.

## Overview

In this project, we train a DQN agent to learn and perform tasks in the OpenAI Gym environment. The trained DQN agent is saved as a Keras model and can be loaded for evaluation or further use.

## Contents

- `train_dqn.py`: Python script for training the DQN agent.
- `my_dqn_agent.h5`: Saved DQN agent model.
- `evaluate_dqn.py`: Python script for evaluating the DQN agent in the environment.
- `requirements.txt`: List of Python dependencies required to run the code.

## Usage

1. Install the required dependencies by running:

pip install -r requirements.txt

2. Train the DQN agent in drl.ipynb

This script will train the DQN agent in the specified environment and save the trained model as `cartpole.h5`.

3. Evaluate the DQN agent


This script will load the trained DQN agent and run it in the environment to evaluate its performance.

## Dependencies

- Python 3.x
- TensorFlow (compatible with your TensorFlow version)
- OpenAI Gym
- NumPy
- Pygame (for visualization, if applicable)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenAI Gym](https://gym.openai.com/): The Gym library provides various reinforcement learning environments.
- [Keras-RL](https://github.com/keras-rl/keras-rl): A high-level library for reinforcement learning in Keras.
