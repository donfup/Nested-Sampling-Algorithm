# Nested-Sampling-Algorithm
Implementing the nested sampling algorithm to artificial data resembling a 2D Brownian Motion trajectory. 

Files in this directory:

bm_data.m
- A matlab script that creates synthetic trajectory data.

bm_data.txt
- An output of bm_data.m

main.m
- A Matlab script that runs the nested sampling algorithm. It is currently set to load the data in the file ‘bm_data.txt’.

naive_explore.m
- A Matlab script similar to the file ’nested_explore.m’ but “dummed down” in order to understand the function. 

nested_sample.m 
- Matlab file that contains the program for running the nested sampling algorithm

naive_sample.m
- A Matlab script similar to the file ‘nested_sample.m’ that runs the nested sampling algorithm - but again “dummed down’ in order to understand the algorthim.

analyze_params.m
- A Matlab script that gives your standard deviation and average values.

logsumexp.m
- A Matlab function. The logsumexp.m file  can be thought of as a smoothed version of the max function, because whereas the max function is not differentiable at points where the maximum is achieved in two different components, the logsumexp function is infinitely differentiable everywhere.


(C) Courtesy of Frederik Heyde-Petersen
