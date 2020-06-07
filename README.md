# RL Algorithms using PyTorch on OpenAI Gym

You will find here implementations of several deep reinforcement learning (RL) algorithms using PyTorch. I am going to evaluate and compare each on one or more environment from OpenAI Gym. The purpose of this repository is to help kickstart my journey in RL + document my learning experience. I hope it might be useful for other people starting as well. :)

I am planning to write a blog post to accompany this repo, so stay tuned!

## Implementations
- [x] [REINFORCE](https://github.com/BKHMSI/RL-PyTorch/blob/master/reinforce.py) (Monte-Carlo Policy Gradient)
- [x] [DQN](https://github.com/BKHMSI/RL-PyTorch/blob/master/dqn.py) | [Minh et al. 2013](https://arxiv.org/abs/1312.5602)
- [x] [Double DQN](https://github.com/BKHMSI/RL-PyTorch/blob/master/dqn.py) | [van Hasselt et al. 2015](https://arxiv.org/abs/1509.06461)
- [ ] Dueling DQN | [Wang et al. 2016](https://arxiv.org/abs/1511.06581)
- [ ] A2C | [Minh el al. 2016](https://arxiv.org/abs/1602.01783)
- [ ] Rainbow | [Hessel et al. 2017](https://arxiv.org/abs/1710.02298)
- and many more...


## Configs

Each implementation has its own `yaml` configuration file to easily change model and environment parameters. 
