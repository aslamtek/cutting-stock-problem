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

### 🧩 Example Problem

#### Inputs:
```python
board_length = 10
board_width = 8
rectangles = [(5, 5), (5, 2), (7, 3)]
rectangle_demands = [1, 1, 1]

###**But you can change it what you need**


