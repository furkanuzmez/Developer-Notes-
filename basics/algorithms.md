
  ### Algorithms * 
Algorithm is a step-by-step procedure, which defines a set of instructions to be executed in a certain order to get the desired output. Algorithms are generally created independent of underlying languages, i.e. an algorithm can be implemented in more than one programming language.

From the data structure point of view, following are some important categories of algorithms −

-   **Search**  − Algorithm to search an item in a data structure.
    
-   **Sort**  − Algorithm to sort items in a certain order.
    
-   **Insert**  − Algorithm to insert item in a data structure.
    
-   **Update**  − Algorithm to update an existing item in a data structure.
    
-   **Delete**  − Algorithm to delete an existing item from a data structure.

## Characteristics of an Algorithm

Not all procedures can be called an algorithm. An algorithm should have the following characteristics −

-   **Unambiguous**  − Algorithm should be clear and unambiguous. Each of its steps (or phases), and their inputs/outputs should be clear and must lead to only one meaning.
    
-   **Input**  − An algorithm should have 0 or more well-defined inputs.
    
-   **Output**  − An algorithm should have 1 or more well-defined outputs, and should match the desired output.
    
-   **Finiteness**  − Algorithms must terminate after a finite number of steps.
    
-   **Feasibility**  − Should be feasible with the available resources.
    
-   **Independent**  − An algorithm should have step-by-step directions, which should be independent of any programming code.
- [ ] **Analysis of Algorithms**
        Efficiency of an algorithm can be analyzed at two different stages, before implementation and after implementation. They are the following −

-   **_A Priori_  Analysis**  − This is a theoretical analysis of an algorithm. Efficiency of an algorithm is measured by assuming that all other factors, for example, processor speed, are constant and have no effect on the implementation.
    
-   **_A Posterior_  Analysis**  − This is an empirical analysis of an algorithm. The selected algorithm is implemented using programming language. This is then executed on target computer machine. In this analysis, actual statistics like running time and space required, are collected.
    

We shall learn about  _a priori_  algorithm analysis. Algorithm analysis deals with the execution or running time of various operations involved. The running time of an operation can be defined as the number of computer instructions executed per operation. 

## Algorithm Complexity

Suppose  **X**  is an algorithm and  **n**  is the size of input data, the time and space used by the algorithm X are the two main factors, which decide the efficiency of X.

-   **Time Factor**  − Time is measured by counting the number of key operations such as comparisons in the sorting algorithm.
    
-   **Space Factor**  − Space is measured by counting the maximum memory space required by the algorithm.
    

The complexity of an algorithm  **f(n)**  gives the running time and/or the storage space required by the algorithm in terms of  **n**  as the size of input data. 

## Space Complexity

Space complexity of an algorithm represents the amount of memory space required by the algorithm in its life cycle. The space required by an algorithm is equal to the sum of the following two components −

-   A fixed part that is a space required to store certain data and variables, that are independent of the size of the problem. For example, simple variables and constants used, program size, etc.
    
-   A variable part is a space required by variables, whose size depends on the size of the problem. For example, dynamic memory allocation, recursion stack space, etc.
    

Space complexity S(P) of any algorithm P is S(P) = C + SP(I), where C is the fixed part and S(I) is the variable part of the algorithm, which depends on instance characteristic I. Following is a simple example that tries to explain the concept − 

## Time Complexity

Time complexity of an algorithm represents the amount of time required by the algorithm to run to completion. Time requirements can be defined as a numerical function T(n), where T(n) can be measured as the number of steps, provided each step consumes constant time.

For example, addition of two n-bit integers takes  **n**  steps. Consequently, the total computational time is T(n) = c ∗ n, where c is the time taken for the addition of two bits. Here, we observe that T(n) grows linearly as the input size increases.


- [ ] **Searching and Sorting**
- [ ] Greedy Algorithms
- [ ] Dynamic Programming
- [ ] Pattern Searching
- [ ] Backtracking
- [ ] **Divide and Conquer**
-          In divide and conquer approach, the problem in hand, is divided into smaller sub-problems and then each problem is solved independently. When we keep on dividing the subproblems into even smaller sub-problems, we may eventually reach a stage where no more division is possible. Those "atomic" smallest possible sub-problem (fractions) are solved. The solution of all sub-problems is finally merged in order to obtain the solution of an original problem. 
     ### Examples

The following computer algorithms are based on  **divide-and-conquer**  programming approach −

-   Merge Sort
-   Quick Sort
-   Binary Search
-   Strassen's Matrix Multiplication
-   Closest pair (points)

There are various ways available to solve any computer problem, but the mentioned are a good example of divide and conquer approach

- [ ] Graph Algoritms
- [ ] Randomized Algorithms

<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAxNzA2ODgzNV19
-->