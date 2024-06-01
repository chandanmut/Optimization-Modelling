# Optimization-Modelling
Optimization analysis for a $10,000 marketing budget allocation across online, social media, and print advertising channels.
Utilizing a data-driven approach, I tailored revenue functions for each channel and used the Sequential Least Squares Programming (SLSQP) method to maximize total revenue. 
Revenue Functions:
Online Advertising: Exhibits diminishing returns, modeled by a square root function.
Social Media Marketing: Follows a logarithmic function, capturing initial rapid growth and eventual saturation.
Print Advertising: Represented by a diminishing returns function, indicating a rapid initial increase in revenue that tapers off.
Total Revenue Calculation:
The total revenue function sums the revenues from all channels and is subject to a budget constraint.

Optimization Constraints:
The constraint function ensures the total budget allocation sums to $10,000.

Initial Guesses and Bounds:
Initial allocation guesses and non-negative bounds were set for the optimization process to ensure feasible solutions.

Optimization Technique:
The Sequential Least Squares Programming (SLSQP) method was utilized to minimize the negative total revenue, effectively maximizing the actual total revenue.
The results suggest allocating the majority of the budget to social media marketing for optimal revenue generation, with minimal funds allocated to online and print advertising channels. This analysis provides insights for strategic budget allocation in marketing campaigns.
