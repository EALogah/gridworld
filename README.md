# Gridworld Reinforcement Learning
This repository contains the implementationof different learning policies in a simple 5x5 gridworld environment using methods such as solving Bellman equations explicitly, iterative policy evaluation, and value iteration.
# Part 1

## Methods Implemented
Value Iteration

Iterative Policy Evaluation

Bellman Equation 

## Experiment Details

### Value Function Estimation Using:

Solving Bellman equations explicitly.

Iterative policy evaluation.

Value iteration.

## Optimal Policy Determination:

Solving the Bellman optimality equation.

Using policy iteration with iterative policy evaluation.

Policy improvement with value iteration.

# Part 2
## Algorithms Implemented
### Monte Carlo Methods
Exploring Starts: Monte Carlo method with exploring starts.

Epsilon-Soft: Monte Carlo method with an epsilon-soft policy to ensure sufficient exploration.
### Dynamic Policy Iteration
#### Policy Evaluation: Iteratively evaluates a given policy by computing the state-value function.
####  Policy Improvement: Updates the policy based on the evaluated state-value function.
#### Dynamic Environment Consideration: Considers the possibility of random permutations of special states, adjusting the policy accordingly.
### Experiment Details
Modified Gridworld Setup
5x5 grid with terminal states at [2,4] and [4,0] (black boxes).
Special states:
Blue: [0,1] with reward 5, jumps to red [3,2].
Green: [0,4] with reward 2.5, jumps to yellow [4,4] or red [3,2] with 0.5 probability.
Red: [3,2] with reward 0.
Yellow: [4,4] with reward 0.
Off-grid moves: reward -0.5.
Moves between white cells: reward -0.2.
Random starting points.
## Tasks
Monte Carlo Methods:

Implementing the Monte Carlo method with exploring starts.
Implementing the Monte Carlo method with an epsilon-soft policy.
Behavior Policy Evaluation:

Equiprobable moves: Random moves with equal probability.
Importance Sampling: Adjusting for the known dynamics to compute the correct state-value function.
Dynamic Policy Iteration:

Policy evaluation and improvement with consideration for the random permutation of special states.
Results and Analysis
The detailed results and analysis are provided in the report.pdf file.
Plots are generated to visualize the value functions obtained using different methods.

# Requirements
Python 3.x
NumPy
Matplotlib
Seaborn

# Installation
Clone the repository and install the required packages:

# Usage
Run the GridWorld.ipynb and NewGridWorld.ipynb scripts to execute the methods and generate the plots:

# Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

# License
This project is licensed under the MIT License.
