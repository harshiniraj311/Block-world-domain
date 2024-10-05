# Block World Domain with Heuristic value 

This repository contains a Python implementation of the Block World problem solved using the A* algorithm with heuristic values. The implementation includes both a step-by-step textual output and an animated visualization of the solution.

## Features

- **A\* Algorithm with Heuristic**: Utilizes the A* algorithm with a heuristic function to find the optimal sequence of moves to transform the initial state into the goal state. The heuristic estimates the number of incorrect blocks compared to the goal state.
- **Step-by-Step Output**: Prints each step of the solution to the console, including g (cost), h (heuristic), and f (evaluation function) values.
- **Interactive Animation**: Provides an animated visualization of the solution with "Next" and "Previous" buttons to control the steps.

## Requirements

- Python 3.x
- matplotlib

## Installation

1. Clone the repository and checkout the `heuristic-value-branch`:
    ```bash
    git clone https://github.com/harshiniraj311/Block-world-domain.git
    cd Block-world-domain
    git checkout heuristic-value-branch
    ```

2. Install the required Python packages:
    ```bash
    pip install matplotlib
    ```

## Usage

1. Run the script:
    ```bash
    python main.py
    ```

2. Follow the prompts to enter the initial and goal states.

## Animation

The animation will show the blocks being moved from the initial state to the goal state. Use the "Next" and "Previous" buttons to navigate through the steps. Each step will also display the g (cost), h (heuristic), and f (total evaluation) values.

## Screenshots
### Input
<img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/out1.png" alt="Block World Input" width="550">

### Output
<p float="left">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/out2.png" alt="Block World Output Step 1" width="250" height="250">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/out3.png" alt="Block World Output Step 2" width="250" height="250">
</p>

### Animated output
<p float="left">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/fig%201.png" alt="Figure 1" width="400">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/fig%202.png" alt="Figure 2" width="400">
</p>

<p float="left">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/fig%203.png" alt="Figure 3" width="400">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/fig%204.png" alt="Figure 4" width="400">
</p>

<p float="left">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/fig%205.png" alt="Figure 5" width="400">
  <img src="https://github.com/harshiniraj311/Block-world-domain/blob/heuristic-value-branch/images/fig%206.png" alt="Figure 6" width="400">
</p>
