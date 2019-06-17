# Deep Reinforcement Learning Navigation project

### Introduction

In this repository you can find how an agent moves through Unity's Navigation environment, and learns to solve it
using Deep Reinforcement Learning. It is similar to Unity's Banana Collector environment, but not identical to it.

The environment consists of a large square space in which you can see yellow and blue bananas on the floor. The goal
is to collect as many yellow bananas while avoiding the blue bananas. For every yellow banana that is 
collected the agent receives a reward of +1, and if he picks a blue banana, he receives a reward of -1. One episode of the game 
consists of 300 timesteps, and if the agent succeeds in obtaining an average score of +13in 100 subsequent 
episodes the environment is considered to be solved by the agent.

### Requirements

If you want to run the notebook locally, you need to have Python 3.6 installed.
You do not need to install Unity, but you can follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies).

![alt text](https://github.com/MartijnNaaijer/DeepReinforcementLearningNavigation/blob/master/picture_bananas.png "You like bananas?")


