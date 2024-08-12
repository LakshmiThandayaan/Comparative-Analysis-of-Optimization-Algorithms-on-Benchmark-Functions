README: Global Optimization Using Particle Swarm Optimisation(PSO) and Genetic Algorithm(GA)

# Project Overview

This project explores global optimization techniques for solving mathematical benchmark functions. It utilizes two primary algorithms: Particle Swarm Optimization (PSO) and 
Genetic Algorithm (GA), each designed to efficiently search for global optima in complex, multidimensional spaces.

## Situation:
Optimizing mathematical functions with multiple local minima presents significant challenges. Traditional optimization methods may become trapped in local optima, failing to find the global solution. This project addresses these challenges by implementing PSO and GA, which are well-suited for exploring large search spaces and avoiding premature convergence.

## Task:
The main objective is to apply PSO and GA to a series of mathematical benchmark functions, each with varying degrees of complexity and dimensionality. The goal is to identify the global optima of these functions by tuning the parameters of both algorithms and analyzing their performance.

## Action

* **Algorithm Implementation**: The PSO and GA algorithms were implemented, each with customizable parameters like population size, number of iterations, and mutation rates for GA, and inertia weight, social, and cognitive coefficients for PSO.
* **Parameter Tuning**: Extensive experimentation was conducted to tune the parameters of both algorithms to balance exploration and exploitation effectively. This involved adjusting parameters like the number of particles, velocity coefficients, and mutation rates to optimize performance.
* **Fitness Evaluation**: Both algorithms were applied to benchmark functions. The fitness of each candidate solution was evaluated, guiding the search process toward the global optimum.

## Result:
The project successfully demonstrated the ability of PSO and GA to find global optima in complex search spaces. The tuned algorithms consistently outperformed basic implementations, showing improved convergence rates and higher accuracy in locating global optima or near global optima results across various benchmark functions.

