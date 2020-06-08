# RL Algorithms using PyTorch on OpenAI Gym

You will find here implementations of several deep reinforcement learning (RL) algorithms using PyTorch. I am going to evaluate and compare each on one or more environment from OpenAI Gym. The purpose of this repository is to help kickstart my journey in RL + document my learning experience. I hope it might be useful for other people starting as well. :)

I am planning to write a blog post to accompany this repo, so stay tuned!

<table>
    <tr>
        <td align="center"><img alt="Lunar Lander v2" src="assets/ddqn-lunar-v2.gif"></td>
        <td align="center"><img alt="CartPole v0"     src="assets/ddqn-cartpole-v0.gif"></td>
    </tr>
</table>


## Implementations
| Algorithm                                                                                          | Features                                        | Paper                                                      |
|: ------------------------------------------------------------------------------------------------- |:----------------------------------------------  |:--------------------------------------------------         |
| <ul><li> [x] [REINFORCE](https://github.com/BKHMSI/RL-PyTorch/blob/master/reinforce.py) </li></ul> | Baseline, Causality                             | [Williams 1992](https://link.springer.com/content/pdf/10.1007/BF00992696.pdf) |
| <ul><li> [x] [DQN](https://github.com/BKHMSI/RL-PyTorch/blob/master/dqn.py)  </li></ul>            | Huber Loss, Gradient Clipping, Polyak Averaging | [Minh et al. 2013](https://arxiv.org/abs/1312.5602)         |
| <ul><li> [x] [Double DQN](https://github.com/BKHMSI/RL-PyTorch/blob/master/dqn.py) </li></ul>      | Same as above                                   | [van Hasselt et al. 2015](https://arxiv.org/abs/1509.06461) |
| <ul><li> [ ] Dueling DQN                                                           </li></ul>      |                                                 | [Wang et al. 2016](https://arxiv.org/abs/1511.06581)        |
| <ul><li> [ ] A2C                                                               </li></ul>          |                                                 | [Minh el al. 2016](https://arxiv.org/abs/1602.01783)        |
| <ul><li> [ ] Rainbow                                                          </li></ul>           |                                                 | [Hessel et al. 2017](https://arxiv.org/abs/1710.02298)      |
| <ul><li> [ ] and many more...                                                 </li></ul>           |                                                 |                                                             |


<!-- - [x] [REINFORCE](https://github.com/BKHMSI/RL-PyTorch/blob/master/reinforce.py) (Monte-Carlo Policy Gradient)
- [x] [DQN](https://github.com/BKHMSI/RL-PyTorch/blob/master/dqn.py) | [Minh et al. 2013](https://arxiv.org/abs/1312.5602)
- [x] [Double DQN](https://github.com/BKHMSI/RL-PyTorch/blob/master/dqn.py) | [van Hasselt et al. 2015](https://arxiv.org/abs/1509.06461)
- [ ] Dueling DQN| [Wang et al. 2016](https://arxiv.org/abs/1511.06581)
- [ ] A2C | [Minh el al. 2016](https://arxiv.org/abs/1602.01783)
- [ ] Rainbow | [Hessel et al. 2017](https://arxiv.org/abs/1710.02298)
- [ ] and many more... -->


## Configurations

Each implementation has its own `yaml` config file to easily change model and environment parameters. 
