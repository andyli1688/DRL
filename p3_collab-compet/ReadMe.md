## Project Details

For this project, we will train an agent to navigate the Tennis environment.

![SegmentLocal](images/tennis.png "segment")

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

## Environment Details

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.

The state for the first agent looks like: [ 0.          0.          0.          0.          0.          0.
  0.          0.          0.          0.          0.          0.
  0.          0.          0.          0.         -6.65278625 -1.5
 -0.          0.          6.83172083  6.         -0.          0.        ] 
 
 
## Every entry in the action vector should be a number between -1 and 1.

Solving Criteria: 

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## Getting Started

### Set up python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.
	- __Mac OSX__: 
	```bash
	conda create --name drlnd python=3.6
	conda activate drlnd
	```
2. Create a DRLND folder and Perform a minimal install of OpenAI gym.  
	```bash
    cd DRLND
    git clone https://github.com/openai/gym.git
    cd gym
    pip install -e .
    cd ..
	```
3. Clone the DRLND repository, and navigate to the `python/` folder.  Then, install several dependencies.
    ```bash
    git clone https://github.com/udacity/deep-reinforcement-learning.git
    cd deep-reinforcement-learning/python
    pip install .
    ```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
```

5. Download the Unity Environment 
   - __Mac OSX__: [Tennis.app.zip](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)


6. Place the unzipped file (Tennis.app) in the p3_collab-compet/ folder in the DRLND GitHub repository.

## Instructions

### Run the code in this repository, follow the instructions below.

1. Open a jupyter Notebook in the DRLND environment
```bash
conda activate drlnd
jupyter notebook
```

2. Navigating to p1_navigation/ folder and open the Navigation.ipynb


3. Before running code in the notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 
![SegmentLocal](images/kernel.png)


4. Use 'Shift-Enter' to run codes line by line and watch how the agent gets trained!


```python

```
