# MaxCut_qosf_screening_tasks
 


## Task 4 
"The MaxCut problem is a well-known optimization problem in which the nodes of a given undirected graph have to be divided in two sets (often referred as the set of “white” and “black” nodes) such that the number of edges connecting a white node with a black node are maximized. The MaxCut problem is a problem on which the QAOA algorithm has proved to be useful ."


## Motivation 
MaxCut problem is a problem thet is use as a proof of concept for  showcase  the  abiliy of quantum algorithms. In the past I approatch to solve these problem but using other thenic called Full Quantum Eigensolver (FQE)[https://github.com/VoicuTomut/QuantumExperiments/tree/master/MaxCut].  I know that MaxCut problem can be solved using Grover and  Variation Quantum Eigansolver (VQE) is also a solution for these problem. 
I like how this problem is used as a toy for algorithms so now I will learn QAOA.

## This repo is organized as follow:


- QAOA_MaxCut_Qiskit
    * Here I solved  MaxCut problem for weighted graphs implementing QAOA in Qiskit.
    
        
- QAOA_MaxCut_Pennylane_Adagard
    * I adapted the Pennylane tutorial to solve MaxCut problem for weighted graphs.
   
   
- QAOA_MaxCut_Pennylane_Adam
    * I adapted the Pennylane tutorial to solve MaxCut problem for weighted graphs using Pennylane and use ADAM as optimizer. 

- tootls 
    * Useful functions in calculating the expected value of an observable


