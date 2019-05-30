# Project Details

[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"


# Project 2: Continuous Control

### Introduction

For this project, you will work with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

## Getting Started

I assume you're operating on Linux and have conda installed along with
CUDA and an nvidia graphics card with the latest drivers.


### Load the conda environment

```conda env create -f environment.yml```
```conda activate drlnd```

### Download the Unity Environment

Linux: click here [https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip]

Unzip and move it into the repo.

### Training the Agent 

```jupyter-notebook```

And then run all the cells to watch the agent train!

When the environment is solved the weights will be saved as
`final_checkpoint_actor.pth` and `final_checkpoint_critic.pth`
