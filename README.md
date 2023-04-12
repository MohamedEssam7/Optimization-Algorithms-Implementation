# Random Search Techniques for Optimization - ITI Course
This repository contains the implementation of three random search techniques for optimization for the purpose of solving the traveling salesman problem (TSP). The course covers a variety of optimization algorithms including heuristics, metaheuristics, and neighborhood search algorithms. The implemented algorithms in this repository are:

1. Nearest Neighbour
2. Genetic Algorithm
3. Ant Colony Optimization

## Prerequisites
1. Python 3
2. NumPy
3. Matplotlib

## Results
The results of each algorithm will be displayed in a graph using Matplotlib. The graph will show the best path found by the algorithm and the corresponding distance.

## Algorithms
1. Nearest Neighbour
The nearest neighbour algorithm is a greedy algorithm that starts at an arbitrary city and repeatedly selects the nearest unvisited city as the next city to visit. The algorithm continues until all cities have been visited, at which point it returns to the starting city. The algorithm has a time complexity of O(n^2), where n is the number of cities.
2. Genetic Algorithm
The genetic algorithm is a metaheuristic inspired by the process of natural selection. It starts by creating an initial population of candidate solutions (i.e., tours). The fittest individuals are then selected as Elitizm and the other for reproduction, and crossover and mutation operators are applied to create new offspring. The process continues for a number of generations, with the hope that the population will converge on a near-optimal solution. The time complexity of the genetic algorithm can vary greatly depending on the population size and number of generations.
3. Ant Colony Optimization
Ant colony optimization is a metaheuristic inspired by the foraging behavior of ants. The algorithm starts by placing a number of artificial ants on the graph. Each ant then constructs a tour by probabilistically choosing its next city based on a combination of the distance between the current city and the candidate cities and the amount of pheromone deposited on the edges. The pheromone is updated after each tour based on the quality of the tour. The algorithm continues for a number of iterations, with the hope that the pheromone trails will converge on a near-optimal solution. The time complexity of the ant colony optimization algorithm can vary greatly depending on the number of iterations and the size of the problem.


## Credits
The implementation of these algorithms is based on the explanations and pseudocode provided in the course material.
