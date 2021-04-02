# P1-navigation
Udacity's Deep Reinforcement Learning Nanodegree - Project 1: Navigation

## Project Details

### State Space
The state space is continuous and 37-dimensional. The dimensions capture the velocity of the agent, and includes ray-based perception of objects around the agent's forward direction.

A reward of +1 is achieved by the agent for collecting a yellow banana, with a -1 reward if the agent picks up a blue banana.

### Action Space
There are four discrete actions for the agent to choose from at each time step:

* 0 - walk forward 
* 1 - walk backward
* 2 - turn left
* 3 - turn right

### When is the enviornment solved?
The environment is considered "solved" when the agent is able to receive an average reward, over 100 episodes, of at least +13.

## Getting Started

### Installing dependencies
_These instructions assume that Anaconda is installed (find it [here](https://www.anaconda.com/))_

1. Create (and activate) a new environment with Python 3.6.

   * Linux or Mac:

        `conda create --name drlnd python=3.6`
        
        `source activate drlnd`

   * Windows:
        
        `conda create --name drlnd python=3.6` 
        
        `activate drlnd`

2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.

    * Next, install the classic control environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
    * Then, install the box2d environment group by following the instructions [here](https://github.com/openai/gym#box2d).

3. Clone the repository, and navigate to the python/ folder. Then, install several dependencies.

        `git clone https://github.com/harrylippy/p1-navigation.git`
        `cd deep-reinforcement-learning/python`
        `pip install .`

4. Create an IPython kernel for the drlnd environment.

        `python -m ipykernel install --user --name drlnd --display-name "drlnd"`
        
6. Before running code in a notebook, change the kernel to match the drlnd environment by using the drop-down Kernel menu.

## Instructions

### How to run the code to train the agent
TODO
