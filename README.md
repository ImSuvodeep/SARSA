# SARSA Implementation

## Introduction
This notebook implements the SARSA (State-Action-Reward-State-Action) algorithm, which is a model-free reinforcement learning algorithm that learns from experience using bootstrapping. SARSA is an on-policy method, meaning it follows the same policy that is being optimized while interacting with the environment.

## Environment
The environment used in this implementation is a simple maze represented as a grid world. The agent starts from the top-left corner and aims to reach the goal at the bottom-right corner. The environment is initialized with optional parameters such as exploring starts and shaped rewards.

## Setup
Before running the SARSA algorithm, it is necessary to set up the required libraries and define some helper functions. The setup code includes installing necessary dependencies and defining functions for visualization and evaluation.

## Implementation
The implementation consists of the following main steps:
1. Creating the environment
2. Initializing the action-value table
3. Defining the policy
4. Implementing the SARSA algorithm
5. Evaluating the resulting action-values and policy
6. Testing the resulting agent in the environment

## Usage
To run the SARSA algorithm and visualize the results, follow these steps:
1. Execute the setup code to install dependencies and define helper functions.
2. Create the environment using the `Maze` class.
3. Initialize the action-value table using numpy arrays.
4. Define the policy function.
5. Implement the SARSA algorithm using the `sarsa` function.
6. Evaluate the resulting action-values and policy using visualization functions.
7. Test the resulting agent using the `test_agent` function.

## Conclusion
SARSA is a simple yet effective reinforcement learning algorithm for solving problems in environments with discrete state and action spaces. This implementation provides a hands-on example of how SARSA can be applied to learn an optimal policy for navigating through a maze-like environment.

For more information about SARSA and reinforcement learning, refer to the relevant literature and documentation.

