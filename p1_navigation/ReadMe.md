## Project Details

For this project, we will train an agent to navigate (and collect bananas!) in a large, square world.
![SegmentLocal](images/banana_project.gif "segment")

A reward of +1 is provided for collecting a `yellow` banana, and a reward of -1 is provided for collecting a `blue` banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

## Environment Details

The simulation contains a single agent that navigates a large environment.  
At each time step, it has four actions at its disposal:
- `0` - walk forward 
- `1` - walk backward
- `2` - turn left
- `3` - turn right

The state space has `37` dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  

Reward: A reward of `+1` is provided for collecting a yellow banana, and a reward of `-1` is provided for collecting a blue banana. 

Solving Criteria: The agent is able to receive an average reward (over 100 episodes) of at least `+13`.  

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
   - __Mac OSX__: [Banana.app.zip](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)


6. Place the unzipped file (Banana.app) in the p1_navigation/ folder in the DRLND GitHub repository.

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
