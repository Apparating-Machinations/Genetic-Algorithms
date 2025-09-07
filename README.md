# Genetic Algorithms Projects

This repository contains projects that explore **evolutionary algorithms** applied to real-world and physics-based problems.

## Notebooks
1. **Vehicle Routing Problem (VRP)**
   - Implements a **genetic algorithm** to solve routing challenges.
   - Optimizes for **total distance** and **load balance** across multiple vehicles.
   - Uses **custom fitness functions**, **partial matching crossover**, and **mutation operators**.
   - Visualises routes and tracks fitness evolution.
   - Extends the basic problem by adding:
     - Capacity constraints for vehicles.
     - Multiple objectives: distance, balance, and capacity penalty.
     - Multi-objective optimisation using NSGA-II.
     - Precomputed distance matrix for efficiency.
     - Pareto front visualisation to explore trade-offs.
   - Provides a more realistic and scalable approach for solving VRP problems.


2. **Karl Sims Inspired Evolutionary Simulation**
   - Builds a **2D physics-based simulation** using **PyMunk**.
   - Evolves **block-based creatures** through **genetic algorithms** with realistic dynamics.
   - Implements **custom mutation logic** and accurate **moment of inertia calculations**.
   - Visualises creature behaviours over generations.

## Libraries Used
- `deap` – for evolutionary algorithm frameworks
- `numpy` – for numerical computations
- `matplotlib` – for plotting results
- `pymunk` – for physics-based simulation
