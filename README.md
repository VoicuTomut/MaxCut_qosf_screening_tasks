# MaxCut_qosf_screening_tasks
 


## Task 4 
"The MaxCut problem is a well-known optimization problem in which the nodes of a given undirected graph have to be divided in two sets (often referred as the set of “white” and “black” nodes) such that the number of edges connecting a white node with a black node are maximized. The MaxCut problem is a problem on which the QAOA algorithm has proved to be useful (for an explanation of the QAOA algorithm you can read this blogpost)."


## Motivation 
MaxCut problem is a problem thet is use as a proof of concept for  showcase  the  abiliy of quantum algorithms. In the past I approatch to solve these problem but using other thenic called Full Quantum Eigensolver (FQE) [ ] .  I know that MaxCut problem can be solved using Grover and  Variation Quantum Eigansolver (VQE) is also a solution for these problem. 
I saw these task as a good oportunity to recap all these algorithms and make a compartion between them.

## This repo is organized as follow:


- Maxcut_QAOA_01.ipynb
       - Here I solved  MaxCut problem for weighted graphs using QAOA and Qiskit.
        - Observation
        
- Maxcut_QAOA_02.ipynb
        - Here I solved  MaxCut problem for weighted graphs using Pennylane.
        - Observation 
        
- Maxcut_VQE_03.ipynb 
        - Here I solved  MaxCut problem for weighted graphs using Quantum Gradient Descendent.

- Maxcut_FQE_04.ipynb
        - Since my last implementation now IBM quanutm proccesors it allow you to do intermediat measurements
        - My firs atttempt can be found here:
        - Some notes:

 
 
