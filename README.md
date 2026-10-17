# Reinforcement Learning Experiments

TD3 navigation, DDPG actor-critic networks and tabular Q-learning environments.

| Notebook | What it covers | Stage |
| --- | --- | --- |
| [09_td3_vehicle_navigation.ipynb](09_td3_vehicle_navigation.ipynb) | Custom grid observations, CNN features and a TD3 agent for a simulated navigation task. | Prototype |
| [21_ddpg_actor_critic.ipynb](21_ddpg_actor_critic.ipynb) | PyTorch actor/critic networks, replay memory and a DDPG training loop. | Prototype |
| [49_mountaincar_q_learning.ipynb](49_mountaincar_q_learning.ipynb) | Discretized MountainCar states, tabular Q-learning, saved Q tables and reward plots. | Learning experiment |
| [54_taxi_q_learning.ipynb](54_taxi_q_learning.ipynb) | Tabular Q-learning and an exploration-decay policy for the Taxi environment. | Learning experiment |

## Running these notebooks

NumPy, Matplotlib, PyTorch and Gym/Gymnasium. TD3 additionally uses Stable-Baselines3. These historical experiments use different environment APIs; choose an environment compatible with the notebook you are running.

Open one notebook in Colab or Jupyter, read its setup cells, set the input paths, and then run the sections you need. Training and network operations are not run automatically by this repository.

## About this collection

These notebooks are organised from an existing Colab archive. The table identifies project experiments, prototypes and learning exercises. Dataset files and model weights are supplied separately. GPU training and external-data workflows were not rerun during preparation.

[Browse all AI, ML and automation topics](https://github.com/captof-omuamua/Colab-AI-ML-Projects).

## Recovered semester exercises

The [semester exercise showcase](semester-exercises/README.md) adds a Tkinter Double Q-learning grid world, historical learning curves, and a MountainCar script variant.

| Material | Purpose |
| --- | --- |
| [Double Q-learning notebook](semester-exercises/double-q-learning.ipynb) | Distinct tabular grid-world exercise; requires a desktop display for Tkinter. |
| [MountainCar script](semester-exercises/mountain_car_q.py) | Script form of the discretized MountainCar exercise represented by the existing notebook. |
| [Archived learning curves](semester-exercises/README.md#preserved-results-and-examples) | Saved notebook outputs, not a fresh evaluation. |

These additions consolidate the former `reinforcement-learning-exercises` repository into this collection. The generic Pendulum DDPG notebook does not establish that it implements the separate warehouse-navigation report.
