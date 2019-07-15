# RL-DDPG
PyTorch implementation of DDPG, tested on OpenAI Gym environments.

Solves the `'LunarLanderContinuous-v2'` environment task in a few hundred epsisodes:
![](https://github.com/steevsteev/RL-DDPG/blob/master/assets/learning%20curve.png)

**WARNING** github seems to have problems rendering .ipynb files (including my notebook), so use this link to view the main.ipynb: https://nbviewer.jupyter.org/github/sshish/RL-DDPG/blob/master/main.ipynb

## Requirements
* Python 3
* PyTorch
* CUDA support (can be disabled by editing the few lines in the code that contain `cuda`)
* OpenAI Gym
* the `hiddenlayer` python module for dynamic plots

## Usage
* run the notebook (main.ipynb)
