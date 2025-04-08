# BOMST_Benchmark
This repository contains a benchmark of 270 instances of the bi-objective minimum spanning tree (BOMST) problem, divided by the maximum cost of each of the graph's edges, indicated in the format SetR, where R is the range. The values for the range can be 100, 1000 and 1000. The following subfolders are divided by correlation (-0.8, 0.0 and 0.8) and size (50, 100 and 150). Instances' name have the following format:

	dataNcorrCseedS.txt

where N = number of nodes, C = correlation factor (used to promote conflict between edge costs and, thus, objective functions), and S = seed (RNG). The graphs are complete.
	
The nondominated points are provided in the corresponding file, NDdataNcorrRseedS.txt, for each instance. Note that some instances could not be solved in 1 hour. In this case, the nondominated points file is empty.
