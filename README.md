# Autonomous Lunar Lander using Deep Q-Learning

Trained a DQL agent to autonomously land a lunar module safely 
on the moon's surface using reinforcement learning.

## Algorithm
- Deep Q-Network (DQN) with 3 hidden layers
- Experience Replay with 100K memory buffer
- ε-greedy policy (ε: 1.0 → 0.01)
- Target network updated every 4 timesteps

## Hyperparameters
- Discount factor γ = 0.995
- Learning rate α = 0.001
- Episodes = 2000
- Max timesteps per episode = 1000

## Result
Agent achieved mean reward > 200 over 2000 episodes,
surpassing the environment's solve threshold.

## Tech Stack
Python, TensorFlow, Keras, OpenAI Gym, NumPy

## Course
Andrew NG Machine Learning Specialization | Coursera