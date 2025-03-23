# 🤖 AI Interaction with Reinforcement Learning 🏆

This repository contains the Jupyter Notebook `AI_Interaction.ipynb`, which leverages reinforcement learning to automate web-based tasks.

## 📜 Description
The notebook defines a custom AI environment using `gymnasium`, trains an agent using `stable-baselines3` (PPO algorithm), and provides an interactive UI using `Gradio`.

## 🛠️ Tools & Libraries Used
- 🎮 **Gymnasium** - For creating reinforcement learning environments
- 🏆 **Stable-Baselines3 (PPO)** - For training AI agents
- 🔥 **Torch** - For deep learning computations
- 📊 **NumPy** - For numerical processing
- 🎨 **Gradio** - For interactive UI

## 📝 Sample Code
```python
import gymnasium as gym
from stable_baselines3 import PPO
import numpy as np

class WebAutomationEnv(gym.Env):
    def __init__(self):
        super(WebAutomationEnv, self).__init__()
        self.state = 0
        self.action_space = gym.spaces.Discrete(3)
        self.observation_space = gym.spaces.Discrete(10)
```

## 📜 License
This project is licensed under the MIT License. 📄
