# Reinforcement_Learning.ipybn

## Description:
This Jupyter Notebook contains a Python implementation of a modified Q-Learning agent for a reinforcement learning task in a custom environment. The environment, resembling a robot navigating a grid to avoid obstacles and reach targets, is built using the 'gym' library.

Key Components:
1. ModifiedQLearningAgent: A class implementing a modified version of the Q-learning algorithm.
2. RobotEnv: A custom environment class, inheriting from gym.Env, representing a grid world with a robot and obstacles.
3. Training functions: Functions to train the Q-learning agent in the RobotEnv.

## Dependencies:
- gym: Provides the environment base class and spaces.
- numpy: Used for numerical computations and array manipulations.
- matplotlib: For visualizing the environment and plotting training results.
- IPython.display: To clear outputs for dynamic rendering in Jupyter Notebook.

## Functionality:
- The ModifiedQLearningAgent class includes methods for choosing actions, updating the Q-table, and decaying the exploration probability.
- The RobotEnv class defines the environment, including the action and observation spaces, and the logic for the robot's movement, reward calculation, and rendering.
- The training functions run episodes where the agent interacts with the environment, learning to navigate it effectively.

## Usage:
To use this notebook, run all cells. The final section of the notebook visualizes the training process and the results, including plots of rewards and moves over episodes.

## Note:
Adjust the number of episodes, learning rate, and other parameters as needed to experiment with the agent's learning process.
