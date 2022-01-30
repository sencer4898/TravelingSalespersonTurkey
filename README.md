# TravelingSalespersonTurkey
Travelling Salesperson problem solved for 81 cities of Turkey.

It is possible to adapt the code for different problems. You just need to change the distance matrix and indexes etc. (First 5-10 cells)

Also, default solver of the PuLP library (COIN-OR solver) is not efficient for this problem. It is possible to change it to GUROBI or CPLEX,
if you wish to solve a larger TSP problem.
