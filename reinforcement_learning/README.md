# Reinforcement Learning

| Notebook | What it covers | Stage |
| --- | --- | --- |
| [09_td3_vehicle_navigation.ipynb](09_td3_vehicle_navigation.ipynb) | Custom grid observations, CNN features and a TD3 agent for a simulated navigation task. | Prototype |
| [21_ddpg_actor_critic.ipynb](21_ddpg_actor_critic.ipynb) | PyTorch actor/critic networks, replay memory and a DDPG training loop. | Prototype |
| [49_mountaincar_q_learning.ipynb](49_mountaincar_q_learning.ipynb) | Discretized MountainCar states, tabular Q-learning, saved Q tables and reward plots. | Learning experiment |
| [54_taxi_q_learning.ipynb](54_taxi_q_learning.ipynb) | Tabular Q-learning and an exploration-decay policy for the Taxi environment. | Learning experiment |

## Running these notebooks

NumPy, Matplotlib, PyTorch and Gym/Gymnasium. TD3 additionally uses Stable-Baselines3. These historical experiments use different environment APIs; choose an environment compatible with the notebook you are running.

Open one notebook in Colab or Jupyter, read its setup cells, set the input paths, and then run the sections you need. Training and network operations are not run automatically by this repository.
