## Project Details

For this project, we will train an agent to navigate the Reacher environment.

![SegmentLocal](images/reacher.gif "segment")

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

## Environment Details

The simulation contains a single agent that navigates a large environment.  
At each time step, it has 33 variables corresponding to:
- Position
- Rotation
- Velocity
- Angular Velocities of the arm

Each action is a vector with four numbers, corresponding to torque applicable to two joints. 

A sample output is shown as below.

Number of agents: 1

Size of each action: 4

There are 1 agents. Each observes a state with length: 33

The state for the first agent looks like: 
[ 0.00000000e+00 -4.00000000e+00  0.00000000e+00  1.00000000e+00
 -0.00000000e+00 -0.00000000e+00 -4.37113883e-08  0.00000000e+00
  0.00000000e+00  0.00000000e+00  0.00000000e+00  0.00000000e+00
  0.00000000e+00  0.00000000e+00 -1.00000000e+01  0.00000000e+00
  1.00000000e+00 -0.00000000e+00 -0.00000000e+00 -4.37113883e-08
  0.00000000e+00  0.00000000e+00  0.00000000e+00  0.00000000e+00
  0.00000000e+00  0.00000000e+00  5.75471878e+00 -1.00000000e+00
  5.55726671e+00  0.00000000e+00  1.00000000e+00  0.00000000e+00
 -1.68164849e-01]
 
## Every entry in the action vector should be a number between -1 and 1.

Solving Criteria: 

Option 1: Solve the First Version
The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over `100` consecutive episodes.

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
   - __Mac OSX__: [Reacher.app.zip](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)


6. Place the unzipped file (Banana.app) in the p2_continuous-control/ folder in the DRLND GitHub repository.

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
