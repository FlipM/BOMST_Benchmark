# BOMST_Benchmark
This repository contains a benchmark of 270 instances of the bi-objective minimum spanning tree (BOMST) problem, divided by the maximum cost of each of the graph's edge:
	- SetsHundred:  Edge cost at most 10^2.
	- Sets1k: Edge cost at most 10^3 = 1k
	- SetsTk: Edge cost at most 10^4 = 10k = Tk.

Inside each respective folder there are 10 sets of 9 instances each. Instances' names have the following format:

	dataNcorrRseedS.txt

where N = number of nodes, R = correlation factor (used to promote conflict between edge costs and, thus, objective functions), and S = seed (RNG). The graphs are complete.
	
For each instance, the nondominated points are provided in the corresponding file, named NDdataNcorrRseedS.txt. Note that some instances could not be solved in 1 hour. In this case, the nondominated points file is empty.
