# Navigation

---
In this project, Deep Reinforcement Learning is applied to train an agent collecting bananas, 
while navigating in a large, square world. It uses a simplified version provided by Udacity of the Unity ML-Agents environment.
  


![alt-text](banana.gif)


The simulation contains a single agent that has four actions at its disposal:
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. 
Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has `37` dimensions and contains the agent's velocity, along with ray-based perception of objects around 
the agent's forward direction. 

Given this information, the agent has to learn how to best select actions. Four discrete actions are available, 
corresponding to:

- `0` - walk forward 
- `1` - walk backward
- `2` - turn left
- `3` - turn right


A reward of `+1` is provided for collecting a yellow banana, and a reward of `-1` is provided for collecting a blue banana. 
The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.


## Setup

Running the simulation locally assumes that python version 3.6x is already installed.  
Additional steps to set up the environment are listed below.

### Install required python libraries

Required dependencies are provided in the [requirements](requirements.txt) file.

The packages can be installed from the command line using pip:
```console
foo@bar:~$ pip install -r requirements.txt
```

### Install the environemt

The simplified version of the environment is already built and can be downloaded from one of the links below. Select the environment that matches your operating system:

- [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

After downloding, simply unzip the file.

### Getting Started

All step on how to get started, for example how to train an agent 
are described in the [Navigation.ipynb](Navigation.ipynb) notebook.


The notebook imports the following python sources:
 - [agent.py](agent.py) Specifies the agent's behavior.
 - [train.py](train.py) Implements the learning algorithm.
 - [model.py](model.py) Defines the network architecture used by the learning algorithm.

