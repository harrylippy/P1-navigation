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

### Downloading the environment
Download the environment from one of the links below. Please select the environment that matches your operating system:

Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a [virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

Place the file in the DRLND GitHub repository, in the p1_navigation/ folder, and unzip (or decompress) the file.
### Installing dependencies
_These instructions assume that Anaconda is installed (find it [here](https://www.anaconda.com/))_

1. Create (and activate) a new environment with Python 3.6.

    **_Linux or Mac:_**

        conda create --name drlnd python=3.6
        source activate drlnd

    **_Windows:_**
        
        conda create --name drlnd python=3.6
        activate drlnd

2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.

    * Next, install the classic control environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
    * Then, install the box2d environment group by following the instructions [here](https://github.com/openai/gym#box2d).

3. Clone the repository, and navigate to the python/ folder. Then, install several dependencies.

        git clone https://github.com/harrylippy/p1-navigation.git
        cd deep-reinforcement-learning/python
        pip install .

4. Create an IPython kernel for the drlnd environment.

        python -m ipykernel install --user --name drlnd --display-name "drlnd"
        
6. Before running code in a notebook, change the kernel to match the drlnd environment by using the drop-down Kernel menu.

## Instructions

### How to run the code to train the agent
All of the code necessary to train the agent is included in the IPython notebook. To run the notebook, execute the following command:

        jupyter notebook Navigation.ipynb
