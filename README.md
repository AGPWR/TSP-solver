# TSP-solver

"Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?" 

This problem is classified as NP-hard in the field of combinatorial optimization and holds significance in both theoretical computer science and operations research. Therefore, we utilize heuristics and metaheuristics as techniques to tackle this problem.


# Solving TSP with different approaches:

1. MST with DFS
2. Local-search
3. Tabu-search
4. Simulated annealing
5. Genetic algorithm


# Files:
- genetic.hpp - contains implementation of genetic metaheuristic
- graph.hpp - basic graph implementation
- local-search.hpp - contains implementation of local-search heuristic
- simulated-annealing.hpp - contains implementation of simulated-annealing metaheuristic
- tabu-search.hpp - contains implementation of tabu-search metaheuristic
- tsp.cpp - main file with tests for all implemented techniques
- utils.hpp - some graph functions
- visualizer.py - plots generator

