# Deep Reinforcement Learning Navigation project

### Introduction

In this repository you can find how an agent moves through Unity's "Bananas" environment, and learns to solve it
using reinforcement learning. It is similar to Unity's Banana Collector environment
The environment consists of a large square space in which you can see yellow and blue bananas on the floor. The goal
is to collect as many yellow bananas as possible while avoiding the blue bananas. For every yellow banana that is 
collected the agent receives a reward of +1, and if he picks a blue banana, he receives a reward of -1. In one episode
 of the game. One episode consists of 300 timesteps, and if the agent succeeds in obtaining an average score of +13
in 100 subsequent episodes the environment is considered to be solved by the agent.

![alt text](https://github.com/MartijnNaaijer/DeepReinforcementLearningNavigation/blob/master/picture_bananas.png "You like bananas?")

### Requirements

For this environment you need to have Python three installed.
You do not need to install Unity, but you can follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies).
