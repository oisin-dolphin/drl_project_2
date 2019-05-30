# Project Details

## Environment


## State and Action spaces

Each agent receives a state space of size 37 and has to produce an action
vector of size 4.

The goal of the environment is for the agent to keep the tip of it's arm within
the sphere.

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
