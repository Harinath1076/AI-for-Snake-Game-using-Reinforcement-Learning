# AI-for-Snake-Game-using-Reinforcement-Learning
Developing an AI Agent to Play Snake “I hypothesize that reinforcement learning models, specifically Q-learning and Deep Q-Networks (DQN), can improve the performance and survival of a Snake AI player by maximizing score and minimizing collisions.”
The Snake game presents a dynamic environment where the player controls a snake to eat food, grow longer, and avoid collisions with walls or its own body. This project aims to develop an AI agent capable of autonomously playing the Snake game using Reinforcement Learning (RL) techniques, specifically Q-learning and Deep Q-Networks (DQN).

The AI's goal is to maximize its score by efficiently collecting food while surviving for as long as possible. Python and PyGame are used to build the game environment, PyTorch for implementing the RL model, and Matplotlib for visualizing the agent's training progress and performance.

Features
Autonomous Gameplay: The AI learns to play Snake by optimizing its actions based on rewards and penalties.
Dynamic State Representation: Encodes snake's position, food location, distances to walls, and its own body for better decision-making.
Real-Time Performance Tracking: Visualizes scores, rewards, and learning progress using Matplotlib.
Reinforcement Learning Techniques: Utilizes Q-learning and DQN for training.

Tools
Python: Main programming language for implementation.
PyGame: Handles game environment creation and interactions.
PyTorch: Implements the RL algorithms and Q-network.
Matplotlib: Visualizes metrics like scores and cumulative rewards.
GitHub: Version control and collaboration.

Reinforcement Learning Approach
Q-Learning:

Q-learning is a model-free RL algorithm that updates the Q-value of a state-action pair using the Bellman equation:
Q(s,a)←Q(s,a)+α(r+γmaxQ(s',a')−Q(s,a))
s: Current state, a: Action, r: Reward, s': Next state.
α: Learning rate, γ: Discount factor.


Deep Q-Network (DQN):

Combines Q-learning with a neural network to approximate Q-values for high-dimensional state spaces.
Leverages techniques like experience replay (storing past experiences) and target networks for stability.

## Features
- Fully functional Snake game environment built using PyGame.
- AI agent trained using DQN for dynamic decision-making.
- Visualization of performance metrics (scores, rewards) using Matplotlib.

Install Each Dependency Individually (If Needed)
python --version(download any version of 3.6 and above)

PyGame (Game Environment): pip install pygame==2.6.0

Numpy (Numerical Operations):pip install numpy==1.23.5

Matplotlib (Visualization): pip install matplotlib==3.7.1

PyTorch (Neural Network Library):pip install torch==2.0.1



