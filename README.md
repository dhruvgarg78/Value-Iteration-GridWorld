# Value-Iteration-GridWorld
This project implements the Value Iteration algorithm for solving a GridWorld environment modeled as a Markov Decision Process (MDP). The algorithm iteratively updates the value of each state to converge to the optimal value function and the corresponding optimal policy.

# How It Works:
The grid is initialized with state values set to zero, and the agent moves based on four possible directions (up, down, left, right).
A reward of -1 is applied for each move, and the terminal state at the bottom-right corner has a reward of 0.
The algorithm performs value iteration until the change in state values is smaller than a specified threshold.

# Results:
The results of the value iteration are shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/bc863cff-67bc-4f85-bd85-43df6e789b5f)


# Requirements:
Python 3.x
NumPy
