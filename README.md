# KnapsackGA-Optimization

This repository contains an implementation of the Genetic Algorithm (GA) applied to the 0/1 Knapsack Problem. The project explores how different genetic algorithm configurations—population sizes, selection methods, crossover, and mutation—affect solution quality and convergence rates. The results and analysis provide insights into optimizing GA parameters for similar combinatorial optimization problems.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [GA Configurations](#ga-configurations)
- [Requirements](#requirements)
- [Results](#results)

---

## Project Overview

The 0/1 Knapsack Problem aims to maximize the total value of selected items without exceeding the knapsack's weight limit. This project uses a Genetic Algorithm to approach an optimal or near-optimal solution by simulating evolutionary principles: selection, crossover, and mutation. Key configurations such as population size and selection operators (Roulette Wheel, Tournament Selection) are varied to analyze their impact on solution quality and computational efficiency.

---

## Features

- **Genetic Algorithm (GA)**: Implementation includes selection, crossover, and mutation functions to iteratively improve solution quality.
- **Selection Methods**: Supports both Roulette Wheel Selection and Tournament Selection.
- **Crossover & Mutation**: Crossover and mutation operators are adjustable, allowing experimentation with different configurations.
- **Population Size Variations**: Analyzes the effect of population sizes ranging from small to large on GA performance.
- **Visualization**: Plots and tables showing the progression of fitness values across generations and with different configurations.

---

## GA Configurations

### Configurable Parameters
- **Population Sizes**: Adjustable to observe effects on diversity and convergence rates.
- **Selection Methods**: Roulette Wheel and Tournament Selection.
- **Crossover & Mutation Activation**: Can be toggled to assess their impact on solution improvement.

---

## Requirements

- Python 3.x
- Required libraries: `matplotlib`, `numpy`, `pandas`

## Results
- Selection Alone: Examines the GA's behavior using only the selection operators.
- Crossover and Mutation: Analyzes the impact of crossover and mutation on exploration and solution refinement.
- Population Size Exploration: Compares convergence and solution quality across various population sizes.

