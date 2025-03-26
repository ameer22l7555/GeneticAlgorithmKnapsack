# Genetic Algorithm for Knapsack Problem

This project implements a genetic algorithm to solve the knapsack problem. The knapsack problem is a classic optimization problem where the goal is to maximize the total profit of items placed in a knapsack without exceeding its weight capacity.

## Project Structure

- **22L7555Ai6 (1).ipynb**: The Jupyter Notebook containing the implementation of the genetic algorithm.

## How to Run

1. Ensure you have Python 3 installed on your system.
2. Install the required packages using the command:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the cells to execute the genetic algorithm.

## Genetic Algorithm Details

- **Population Size**: 10
- **Generations**: 100
- **Crossover Rate**: 0.8
- **Mutation Rate**: 0.1

The algorithm uses a tournament selection method, single-point crossover, and mutation to evolve the population over generations.

## Results

The algorithm outputs the best solution found, along with its total profit and weight.

## Dependencies

The project requires the following Python package:
- `random` (part of Python's standard library)

## License

This project is licensed under the MIT License. 