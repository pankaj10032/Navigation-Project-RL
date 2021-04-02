# Deep Reinforcement Learning: Navigation project

This repository contains my work for the first project of the Udacity's course: [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)

## The environment

We use an Unity environment to train and evaluate how our deep reinforcement learning algorithm is capable to learn.</n>

The **objective of the agent** will be to wander around an square world to **collect as much as possible yellow bananas avoiding the blue ones.**

![Navigate to collect yellow bananas](images/navigation_bananas.gif)

A **reward of +1 is provided for collecting a yellow banana**, and a **reward of -1 is provided for collecting a blue banana**. 

The state **space has 37 dimensions** and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. 
Given this information, the agent has to learn how to best select actions. Four discrete **actions** are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

#### GOAL: 
The task is episodic, and in order **to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.**

## Instructions

This project implements a Reinforcement Learning Method called Deep Q-Networks.

To begin, before you clone this repository, you first should configure a Python 3.6 / PyTorch 0.4.0 environment with the needed requirements as described in the [Udacity repository.](https://github.com/udacity/deep-reinforcement-learning#dependencies)

You will also need to configure the environment, to do so, follow the instructions in the [Getting Started Section.](https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md)

Then, you can follow the project in the Navigation notebook: Navigation.ipynb. You will be able to see how the agent learns along the time and it is able to solve the problem in just 407 episodes!

** Note: As it this option is not available in the Udacity's Workspace, it is not possible to see the simulator of the environment.
