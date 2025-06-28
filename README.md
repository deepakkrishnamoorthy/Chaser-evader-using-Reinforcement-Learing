# Chaser-evader-using-Reinforcement-Learing
🎯 A simple 2D reinforcement learning environment where a chaser agent learns to catch an evader using Soft Actor-Critic (SAC). Includes custom Gym environment, training scripts, evaluation, and visualization.
What started as a simple idea — "Can an agent learn to chase another in a 2D space?" — turned into an insightful deep dive into the challenges of sparse rewards, smart evaders, and meaningful learning in reinforcement learning systems.

🚦 Initial attempts?
My chaser agent wandered around, missing the evader every time. With a sparse reward function and a perfectly evasive opponent, the learning signal was nearly zero. Classic case of “RL isn’t working”!

👨‍🔬 But instead of giving up, I decided to treat this like a research loop:

Analyzed reward shaping strategies.

Examined loss and entropy trends.

Evaluated policy collapses and long, ineffective episodes.

Feel free to use the .ipynb file and PY files, the code is pretty self explanatory
