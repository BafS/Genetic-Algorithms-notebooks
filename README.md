# Genetic Algorithms

Authors: Fabien salathe, Paul Ntawuruhunga, Henrik Akesson

Date: 14.06.2016

School: HEIG-VD



## 6.1 The Traveling Salesman Problem (TSP)

The traveling salesman problem, asks the following question: "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?"



![TSP](https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/GLPK_solution_of_a_travelling_salesman_problem.svg/512px-GLPK_solution_of_a_travelling_salesman_problem.svg.png)

[https://en.wikipedia.org/wiki/Travelling_salesman_problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem)

The figure above shows the solution of a TSP: The black line shows the shortest possible path that connects every red dot.

## The problem

Given a set of 14 GPS positions where each coordinate represents a city in Burman (Officially the Replublic of the Union of Myanmar), the objective is to solve the TSP problem on it.

```python
LAT = [16.47, 16.47, 20.09, 22.39, 25.23, 22.00, 20.47, 
        17.20, 16.30, 14.05, 16.53, 21.52, 19.41, 20.09]

LON = [96.10, 94.44, 92.54, 93.37, 97.24, 96.05, 97.02, 
		96.29, 97.38, 98.12, 97.38, 95.59, 97.13, 94.55]
```

## Our solution



