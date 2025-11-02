#Snake AI Game
This project is an AI-powered Snake game built using Python, PyTorch, and Pygame. The AI learns to play the classic Snake game using reinforcement learning, specifically Deep Q-Learning.

Features
Classic Snake game environment created with Pygame.

AI agent controls the snake, learning by trial and error.

Deep Q-Learning algorithm with a neural network predicts optimal moves.

State representation includes danger zones, snake direction, and food position.

Rewards for eating food (+10) and penalties for collisions (-10).

Experience replay to improve learning efficiency.

Training progress tracked through scores and performance improvements over multiple games.

Getting Started
Clone the repository.

Install required dependencies: pip install pygame torch numpy matplotlib.

Run the game and training script to watch the AI learn and play.

How It Works
The AI observes the game state and selects an action (move) that maximizes its expected reward. Using a neural network, it predicts Q-values for possible moves and updates its knowledge through repeated play, balancing exploration and exploitation.

Learning Outcome
This project demonstrated practical reinforcement learning implementation, including state-action design, reward systems, training neural networks, and applying AI in a real-time game environment.
