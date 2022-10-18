# Lab 1 - Set Covering

First lab + peer review. List this activity in your final report, it will be part of your exam.

## Task

Given a number $N$ and some lists of integers $P = (L_0, L_1, L_2, ..., L_n)$, 
determine, if possible, $S = (L_{s_0}, L_{s_1}, L_{s_2}, ..., L_{s_n})$
such that each number between $0$ and $N-1$ appears in at least one list

$$\forall n \in [0, N-1] \ \exists i : n \in L_{s_i}$$

and that the total numbers of elements in all $L_{s_i}$ is minimum. 

## Instructions

* Create the directory `lab1` inside the course repo (the one you registered with Andrea)
* Put a `README.md` and your solution (all the files, code and auxiliary data if needed)
* Use `problem` to generate the problems with different $N$
* In the `README.md`, report the the total numbers of elements in $L_{s_i}$ for problem with $N \in [5, 10, 20, 100, 500, 1000]$ and the total number on $nodes$ visited during the search. Use `seed=42`.
* Use `GitHub Issues` to peer review others' lab

--------------------------------------------------------------

Group Members: Milad Zakhireh, Masoud Karimi

--------------------------------------------------------------

Results achieved through the solution discovered are as below:

for N = 5:  
Found a solution in 3 steps; visited 32 states  
path = [{0}, {0, 1, 3}, {0, 1, 2, 3, 4}]  
W = 9  

for N = 10:  
Found a solution in 3 steps; visited 776 states  
path = [{2, 5}, {1, 2, 5, 6, 8}, {0, 1, 2, 3, 4, 5, 6, 7, 8, 9}]  
W = 17  

for N = 20:  
Found a solution in 4 steps; visited 15,887 states   
path = [{0, 1, 2, 7}, {0, 1, 2, 6, 7, 9, 16, 19}, {0, 1, 2, 3, 5, 6, 7, 8, 9, 10, 13, 14, 16, 17, 19}, {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19}]  
W = 47  
