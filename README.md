
# 2D Cutting Stock Problem Solver

This repository contains a solution to the **2D Cutting Stock Problem** using **linear programming** and a **best-fit heuristic** to minimize waste. The problem aims to cut smaller rectangular pieces from a larger rectangular board in such a way that the total waste is minimized.

## Problem Overview

In the **2D Cutting Stock Problem**, you are tasked with cutting rectangular pieces of various sizes from a larger board. The goal is to:
- Satisfy the demand for each type of rectangle.
- Minimize the waste area (the remaining unused area on the board).
- Allow the rectangles to be placed in different orientations (rotated or not).

## Features

- **Linear Programming (LP)**: The problem is formulated and solved using the **PuLP** library, which minimizes the total waste.
- **Visualization**: The solution is visualized using **matplotlib**, which displays the placement of the rectangles on the board.
- **Best-Fit Heuristic**: A simple heuristic is used to place the rectangles on the board by selecting the best position and orientation to minimize the waste.

## Installation

### Requirements

To run this code, you need to have the following Python libraries installed:

- **PuLP**: For solving the linear programming problem.
- **matplotlib**: For visualizing the solution.

### Installation Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/aslamtek/cutting-stock-problem.git
   cd cutting-stock-problem
