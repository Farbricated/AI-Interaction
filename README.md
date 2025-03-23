# **AI Interaction 🤖🚀**

## **Overview**  
This project leverages reinforcement learning for AI-based interactions using `gymnasium`, `stable-baselines3`, and `Gradio`. The AI is trained using the PPO algorithm to optimize actions in a simulated environment.  

## **Tools & Libraries Used 🛠️**  
- **Gymnasium** – Environment simulation  
- **Stable-Baselines3** – Reinforcement learning (PPO)  
- **Torch** – Deep learning computations  
- **Gradio** – Interactive UI for testing  
- **NumPy** – Numerical processing  

## **Installation & Setup ⚙️**  
Run the following command to install dependencies:  
```bash
pip install gymnasium stable-baselines3 torch gradio numpy
```

## **Usage 🚀**  
Load the notebook and execute the training script to see AI interactions in action. Modify the environment to customize tasks!  

## **Example Code 📝**  
```python
import gymnasium as gym
from stable_baselines3 import PPO

env = gym.make("CartPole-v1")
model = PPO("MlpPolicy", env, verbose=1)
model.learn(total_timesteps=10000)
```

## **License 📜**  
This project is under the MIT License.  
