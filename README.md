# Deep Convolutional Q-Learning for Pac-Man

This repository implements Deep Convolutional Q-Learning (DQN) to teach an AI agent how to play the classic Pac-Man game. Using reinforcement learning, the agent learns optimal strategies by observing the game screen and choosing actions to maximize its score.

# Features
Deep Q-Network (DQN): Utilizes a convolutional neural network to approximate Q-values from raw pixel input.
Replay Memory: Stores past experiences to break correlations in training data.
Epsilon-Greedy Exploration: Balances exploration of the game environment with exploitation of learned strategies.
Target Network: Stabilizes training by decoupling Q-value updates from the current policy.
Frame Stacking: Processes multiple consecutive frames to provide temporal context for the agent.

# Acknowledgment
This repository is inspired by the Artificial Intelligence A-Z course by the SuperDataScience Team, taught by Hadelin de Ponteves, Kirill Eremenko, Luka Anicin, and others.

# Certificate
My course certificate can be found here:  
[![View Certificate](https://img.shields.io/badge/Udemy-Certificate-blue)](https://concordia.udemy.com/certificate/UC-e3586052-f943-46e7-b362-8a8787786feb/)
