# Topological Sorting

Institution: Instituto Superior Técnico - Universidade de Lisboa
Course: Computer Science and Engineering (LEIC)
Academic year: 2016-2017

Authors: Francisco Barros & Rafael Ribeiro

Subject: Analysis and Synthesis of Algorithms (2nd year, 2nd semester)

Project details:
* Objective: Order V elements, representing Mr.John's pictures, based on E relations (dating), between pairs of elements.
* Implentation in: C++  
*
* Solution achieved with: Depth First Search (DFS)
* Time complexity: O(V + E) - linear 
* We define a relation as pair of elements (u, v) such that element u preceeds v if the elements (pictures) were in order.
*
* Compile using linux terminal: $ g++ -o3 -ansi -Wall -o projectSolution projectSolution.cpp
* Execute using linux terminal: $ projectSolution
*
* The input consists of:
* - One line with the number of elements to order (N) and the number of relations L that are known;
* - A list with N lines of relations;
* The output may be one of the following:
* - "Insuficiente" (Insufficient): The given input is not sufficient to find a unique order for the elements;
* - "Incoerente" (Incoherent): The given input is not coherent. For example given elements u, v, k, according to the input element u should come before v which should come before k, which in turn, comes before u (cycle);
* - A line of N elements written in order based on the relations given as input, if the input was both coherent and sufficient.
