# CVRP_Solver_4OMAC
This is the code for CVRP_Solver using OMAC.'Read.py' is used to read CVRP files(P-n19-k2.txt,E-33-k4.txt,E-51-k5.txt). ‘utils.py’ contains some auxiliary functions such as TSP to QUBO modeling, matrix quantization. 'TSP_Solver.py' is a TSP instance solver, which uses the asynchronous HNN algorithm to solve the TSP instances. 'CVRP_Solver.py' is the main program, which includes using the K-means method with capacity constraints to split the CVRP instances into multiple TSP instances and calling TSP_Solver to independently solve each TSP instance.
3 CVRP instances (P-n19-k2.txt,E-33-k4.txt,E-51-k5.txt) are selected from the CVRP database http://vrp.atd-lab.inf.puc-rio.br/index.php/en/.
