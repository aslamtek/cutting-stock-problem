# 📐 2D Cutting Stock Problem Solver

This project provides a solution to the **2D Cutting Stock Problem**, utilizing **linear programming** and a **best-fit heuristic** to minimize material waste when cutting predefined rectangles from a larger board.

---

### 📄 What This README Contains:
- **Problem Overview**: Explanation of the **2D Cutting Stock Problem** and the goal of minimizing waste.
- **Installation Instructions**: Steps to install the required libraries (`PuLP` and `matplotlib`).
- **Usage Instructions**: How to set up and run the code, including the input format and execution.
- **License and Contributions**: Details on the open-source license and how to contribute.

---

### 📦 Problem Overview

The **2D Cutting Stock Problem** involves:
- Cutting various smaller rectangles from a large rectangular board.
- Minimizing the unused (waste) space on the board.
- Meeting demand for each rectangle type.

**Real-World Use Cases**: Furniture manufacturing, glass cutting, textile production, and metal fabrication.

---

### ✨ Features

- 🧠 **Linear Programming** using `PuLP`
- 📐 **Best-Fit Heuristic** for smarter placement
- 📊 **Graphical Visualization** with `matplotlib`

---
To run this code, you need to have the following Python libraries installed:

- **PuLP**: For solving the linear programming problem.
- **matplotlib**: For visualizing the solution.

### Installation Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/aslamtek/cutting-stock-problem.git
   cd cutting-stock-problem

2. Navigate to the project directory:
   ```bash
   cd cutting-stock-problem


3. Install the required dependencies:
   ```python
   pip install pulp matplotlib


### 🧩 Example Problem

### Example Input:
Here is an example of the input data used in the problem:


# Board dimensions
    ```python
    board_length = 20  # Length of the large board
    board_width = 15   # Width of the large board

# Types of rectangles (length, width) and their corresponding demand 
  ```python
  rectangles = [(12, 14), (9, 7), (15, 10), (8, 6), (13, 10), (11, 9), (17, 12), (6, 9), (18, 11)]

# Rectangle demands: How many pieces of each rectangle are needed
  ```python
  rectangle_demands = [3, 4, 2, 1, 3, 2, 2, 3, 1]


4. Run the Cutting Stock Solution:

      ```bash
     python cutting_stock_solution.py


## Visual Representation of the Board

Below is an example of the 2D Cutting Stock Problem solution, showing how the rectangles are placed on the board.

![Cutting Stock Solution](images/cutting_stock_output.png)

