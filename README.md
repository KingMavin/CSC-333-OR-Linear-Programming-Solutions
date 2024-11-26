# CSC-333-OR-Linear-Programming-Solutions
Linear Programming Problem: Product Optimization

Problem Statement:
A factory produces two types of products, A and B. Each product requires a certain amount of machine time and raw materials. The objective is to determine the optimal production quantity for each product to maximize the total profit.

Mathematical Formulation:
Let:

    x = Number of units of product A
    y = Number of units of product B

Objective Function:

    Maximize Profit = 3x + 4y

Constraints:

    Machine Time Constraint:
        2x + 3y ≤ 12
    Raw Material Constraint:
        x + 2y ≤ 8
    Non-negativity Constraints:
        x ≥ 0, y ≥ 0

Solution Approach:
We will use the Python library PuLP to solve this linear programming problem.

Steps to Run the Code:

    Install Required Libraries: Ensure you have PuLP installed. You can install it using pip:
    Bash

    pip install pulp

    Use code with caution.

    Write the Python Code: Create a Python script and implement the linear programming model using the PuLP library.
    Run the Code: Execute the Python script to solve the LP problem and obtain the optimal solution.

Interpretation of Results:
The optimal solution will provide the values of x and y that maximize the profit, given the constraints. This solution will help the factory make informed decisions about production quantities to achieve maximum profitability.
