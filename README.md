# Customer Acquisition & Retention Dynamics

This project models and simulates the dynamics of customer acquisition and retention for a company running a continuous advertising campaign. The relationship between potential and active customers is analyzed using a system of linear ordinary differential equations (ODEs), solved both numerically and analytically.

## Problem Description

Let:
*   $x(t)$ = Number of **potential customers** at time $t$
*   $y(t)$ = Number of **active customers** at time $t$

The system is modeled by the following differential equations:

$$\frac{dx}{dt} = -0.3x + 0.1y + 50$$
$$\frac{dy}{dt} = 0.2x - 0.4y$$

### Initial Conditions
*   $x(0) = 100$
*   $y(0) = 20$

The constant term ($50$) represents the effect of a continuous advertising campaign that attracts 50 new potential customers per unit time.

---

## Tasks & Objectives

1. **Numerical Simulation:** Solve the initial value problem numerically over the interval $0 \leq t \leq 30$ using Python (Google Colab).
2. **Behavioral Analysis:** Plot the trajectories of $x(t)$ and $y(t)$ to interpret customer acquisition and retention behavior over time.
3. **Error Analysis:** Compare the numerical solution against the exact analytical solution by computing the **maximum absolute error** to evaluate approximation accuracy.
4. **Scenario Analysis (Intensified Campaign):** 
    * Increase the recruitment rate from $50$ to $100$ customers per unit time.
    * Simulate the modified system and compare results with the original model.
    * Discuss how intensified advertising impacts both potential and active customer groups using visual graphs and numerical evidence.
