# Full Stack Web Developer
## Ms. Eng. Furkan Üzmez
if there is a star (*) in any subject you can write a blog post about it.
**bold item** -> have to know
normal item -> good to know (at least you should say "hear before") 
## Basics

### Data Structures *
- [x] **Array**
-         Array Dimensions ,  Python has not Array type but list type could be used as Array in Python . 
-         Array functions , push , pop   
- [x] Linked List 
- [ In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list. ] 

 ####    MajorDifferenceswithArray: Important
-   **Size:** Since data can only be stored in contiguous blocks of memory in an array, its size cannot be altered at runtime due to risk of overwriting over other data. However in a linked list, each node points to the next one such that data can exist at scattered (non-contiguous) addresses; this allows for a dynamic size which can change at runtime.
-   **Memory allocation:**  For arrays at compile time and at runtime for linked lists.
-   **Memory efficiency:**  For the same number of elements, linked lists use more memory as a reference to the next node is also stored along with the data. However, size flexibility in linked lists may make them use less memory overall; this is useful when there is uncertainty about size or there are large variations in the size of data elements; memory equivalent to the upper limit on the size has to be allocated (even if not all of it is being used) while using arrays, whereas linked lists can increase their sizes step-by-step proportionately to the amount of data.
-   **Execution time:** Any element in an array can be directly accessed with its index; however in case of a linked list, all the previous elements must be traversed to reach any element. Also, better cache locality in arrays (due to contiguous memory allocation) can significantly improve performance. As a result, some operations (such as modifying a certain element) are faster in arrays, while some other (such as inserting/deleting an element in the data) are faster in linked lists.

- [x] **Stack** 
- [  In case of arrays and linked lists, these two allows programmers to insert and delete elements from any place within the list, i.e., from the beginning or the end or even from the middle also. But in computer programming and development, there may arise some situations where insertion and deletion require only at one end wither at the beginning or end of the list. The stack is a linear data structure, and all the insertion and deletion of its values are done in the same end which is called the _top_ of the stack. Let us suppose take the real-life example of a stack of plates or a pile of books etc. As the item in this form of data structure can be removed or added from the top only which means the last item to be added to the stack is the first item to be removed. So you can say that the stack follows the Last In First Out (LIFO) structure. ] 
- [x] **Queue** 
- [  A queue is a linear list of elements in which deletion of an element can take place only at one end called the front and insertion can take place on the other end which is termed as the rear. The term front and rear are frequently used while describing queues in a linked list. In this chapter, you will deal with the queue as arrays.
	In the concept of a queue, the first element to be inserted in the queue will be the first element to be deleted or removed from the list. So Queue is said to follow the FIFO (First In First Out) structure. A real-life scenario in the form of example for queue will be the queue of people waiting to accomplish a particular task where the first person in the queue is the first person to be served first.]
- [x] Binary Tree 
- [  [  


This chapter explores one of the most important non-linear data structures, i.e., trees. Various kinds of trees are available with different features. You will start learning with the most important tree structure, i.e., the binary tree which is a finite set of elements that is either empty or further divided into sub-trees.

There are two ways to represent binary trees. These are:

-   Using arrays
-   Using Linked lists

**Table of Contents**

[#  The Non-Linear Data structure](https://www.w3schools.in/data-structures-tutorial/binary-trees/#The_Non-Linear_Data_structure)

[#  What is a Binary Tree?](https://www.w3schools.in/data-structures-tutorial/binary-trees/#What_is_a_Binary_Tree)

[#  Applications of Binary Tree](https://www.w3schools.in/data-structures-tutorial/binary-trees/#Applications_of_Binary_Tree)

[#  Types of Binary Trees are](https://www.w3schools.in/data-structures-tutorial/binary-trees/#Types_of_Binary_Trees_are)

## The Non-Linear Data structure

The data structures that you have learned so far were merely linear - strings, arrays, lists, stacks, and queues. One of the most important nonlinear data structure is the tree. Trees are mainly used to represent data containing the hierarchical relationship between elements, example: records, family trees, and table of contents. A tree may be defined as a finite set 'T' of one or more nodes such that there is a node designated as the root of the tree and the other nodes are divided into n>=0 disjoint sets T1, T2, T3, T4  …. Tn  are called the subtrees or children of the root.

## What is a Binary Tree?

A binary tree is a special type of tree in which every node or vertex has either no child node or one child node or two child nodes. A binary tree is an important class of a tree data structure in which a node can have at most two children.

Child node in a binary tree on the left is termed as 'left child node' and node in the right is termed as the 'right child node.'

In the figure mentioned below, the root node 8 has two children 3 and 10; then this two child node again acts as a parent node for 1 and 6 for left parent node 3 and 14 for right parent node 10. Similarly, 6 and 14 has a child node.] 
- [x] Binary Search Tree 
- [ **Binary Search Tree**  is a node-based binary tree data structure which has the following properties:

-   The left subtree of a node contains only nodes with keys lesser than the node’s key.
-   The right subtree of a node contains only nodes with keys greater than the node’s key.
-   The left and right subtree each must also be a binary search tree  ] 
- [x] Heap 
- [  A Heap is a special Tree-based data structure in which the tree is a complete binary tree. Generally, Heaps can be of two types:

1.  **Max-Heap**: In a Max-Heap the key present at the root node must be greatest among the keys present at all of it’s children. The same property must be recursively true for all sub-trees in that Binary Tree.
2.  **Min-Heap**: In a Min-Heap the key present at the root node must be minimum among the keys present at all of it’s children. The same property must be recursively true for all sub-trees in that Binary Tree. ]
 
- [ ] **Hashing** 
- [  **Hash Table** ] 
-   Hash Table is a data structure which stores data in an associative manner. In a hash table, data is stored in an array format, where each data value has its own unique index value. Access of data becomes very fast if we know the index of the desired data.

Thus, it becomes a data structure in which insertion and search operations are very fast irrespective of the size of the data. Hash Table uses an array as a storage medium and uses hash technique to generate an index where an element is to be inserted or is to be located from. 

 Hashing is a technique to convert a range of key values into a range of indexes of an array. We're going to use modulo operator to get a range of key values. Consider an example of hash table of size 20, and the following items are to be stored. Item are in the (key,value) format.

- [ ] Graph 
- [   A graph is a pictorial representation of a set of objects where some pairs of objects are connected by links. The interconnected objects are represented by points termed as **vertices**, and the links that connect the vertices are called **edge** ] 
- [ ] Map, Dictionary

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

### Design Patterns * (only bold patterns are important, just learn the others names)
- [ ] **Creational Patterns**
	- [ ] Abstract Factory
	- [ ] Builder
	- [x] **Factory Method**
	- [ ] Prototype
	- [x] **Singleton**
- [ ] Structural Patterns
	- [ ] **Adapter**
	- [ ] Bridge
	- [ ] Composite
	- [ ] Decorator
	- [ ] Facade
	- [ ] Flyweight
	- [ ] Proxy
 - [ ] Behavioral Patterns
	- [ ] Chain of Responsibility
	- [ ] Command
	- [ ] Interpreter
	- [ ] Iterator
	- [ ] Mediator
	- [ ] Memento
	- [ ] **Observer**
	- [ ] State
	- [ ] Strategy
	- [ ] Template Method
	- [ ] Visitor
 







## Frontend
### Internet *
- [ ] **How does the internet work?**
- [ ] **What is HTTP?, HTTPS?**
- [ ] Content Security Policy
- [ ] CORS
- [ ] OWASP Security Risks
- [ ] **Browsers and how they work?**
- [ ] **DNS and how it works?**
- [ ] **What is Domain Name?**
- [ ] **What is hosting?**
### HTML
- [ ] **Basics**
- [ ] **Forms and Validations**
- [ ] Conventions and Best Practices
- [ ] Accessibility
- [ ] SEO Basics *
### CSS
- [ ] **Basics**
- [ ] **Making Layouts**
- [ ] Responsive Design and Media Queries
- [ ] CSS Grid
- [ ] Flexbox
- [ ] Positioning
- [ ] BEM
- [ ] Sass
- [ ] PostCSS
### JAVASCRIPT
- [ ] **Syntax and Basic Constructs**
- [ ] **Learn DOM Manupulation** *
- [ ] **Learn Fetch API/Ajax (XHR)** *
- [ ] Hoisting *
- [ ] Event Bubbling *
- [ ] Scope
- [ ] Prototype *
- [ ] **Shadow DOM** *
- [ ] strict
- [ ] **ES6+ features** * (like arrow function for ex.)
- [ ] TypeScript *
### Version Control Systems *
- [ ] **git clone**
- [ ] **git branch**
- [ ] **git checkout**
- [ ] **git status**
- [ ] **git add**
- [ ] **git commit**
- [ ] **git push**
- [ ] **git pull**
- [ ] git revert
- [ ] **git merge**
- [ ] git remote
- [ ] git fetch
- [ ] git cherrypick
- [ ] one of the Fork, SourceTree or GitKraken vcs program, (recommended Fork)
### Package Managers
- [ ] **npm**
- [ ] yarn
### Frameworks
- [ ] **React**
- [ ] Angular
- [ ] Vue
### React
- [ ] **Redux***
- [ ] redux-thunk or redux-saga or redux-observable*
### Testing*
- [ ] **Jest**
- [ ] **react-testing-library**
- [ ] **Cypress**
- [ ] **Enzyme**
- [ ] Unit, Integration and Functional Test*
- [ ] Mocha
- [ ] Chai
- [ ] Ava
- [ ] Jasmine
### CSS Frameworks
- [ ] **Bootstrap**
- [ ] Reactstrap
- [ ] Material UI
- [ ] Tailwind CSS
- [ ] Chakra UI
### Progressive Web Apps
- [ ] Storage*
- [ ] Web Sockets*
- [ ] Service Workers*
- [ ] Location
- [ ] Notifications
- [ ] Device Orientation
- [ ] Payments
- [ ] Credentials
- [ ] Calculating, Measuring and Improving performance

### Frontend PLUS+
- [ ] GraphQL
- [ ] GatsbyJS
- [ ] React Native
- [ ] Keep Practicing


## Backend
### OS and General Knowlodge
- [ ] **Terminal Usage (basic commands)***
- [ ] How OSs works in general
- [ ] Process management
- [ ] Threads and concurrency *
- [ ] other terminal commands (grep, awk, sed, lsof, curl, wget, tail, head, less, find, ssh, kill)
- [ ] Memory management
- [ ] Interprocess communication
- [ ] I/O Management
- [ ] POSIX Basics
- [ ] Basic Networking Concepts *
### Master in One Coding Language
- [ ] **JavaScript**
- [ ] **Python**
- [ ] **Java**
- [ ] Go
- [ ] Ruby (Just know the name of it)
- [ ] PHP (Just know the name of it)
- [ ] C# (Just know the name of it)
- [ ] Rust (Just know the name of it)

### Relational Databases
- [ ] **PostgreSQL**
- [ ] MySQL
- [ ] MSSQL
- [ ] Oracle

### NOSQL Databases
- [ ] **MongoDB**
- [ ] RethinkDB (Just know the name of it)
- [ ] CouchDB (Just know the name of it)
- [ ] DynamoDB (Just know the name of it)

### Database Knowlodge
- [ ] **ORMS**
- [ ] **ACID**
- [ ] **Transactions**
- [ ] **N+1 Problem**
- [ ] **Database Normalization**
- [ ] **Indexes and how they work**
- [ ] Data Replication
- [ ] Sharding Strategies
- [ ] CAP Theorem

### APIs
- [ ] **REST**
- [ ] **JSON APIs**
- [ ]  gRPC
- [ ] SOAP
- [ ] **Authentication**
	- [ ]  OAuth
	- [ ] Basic Authentication
	- [ ] Token Authentication
- [ ] HATEOAS
- [ ] Open API Spec and Swagger

### Caching
- [ ] CDN
- [ ] Server Side
- [ ] **Client Side**
- [ ] Redis
- [ ] Memcached

### Web Security Knowlodge
- [ ] SHA Family
- [ ] scrypt and bcrypt
- [ ] MD5 and why not to use it

### Testing
- [ ] Integration Testing
- [ ] **Unit Testing**
- [ ] Functional Testing

### Design and Development Principles
- [ ] SOLID
- [ ] KISS
- [ ] YAGNI
- [ ] DRY
- [ ] GOF Design Patterns
- [ ] Domain Driven Design
- [ ] Test Driven Development

### Architectural Patterns
- [ ] **Monolithic Apps**
- [ ] **Microservices**
- [ ] SOA
- [ ] CQRS and Event Sourcing
- [ ] **Serverless**

### Web Servers
- [ ] Nginx
- [ ] Apache

### Backend Plus+
- [ ] Docker
- [ ] RabbitMQ
- [ ] Kafka
- [ ] Neo4j
- [ ]  Migration Strategies
- [ ] Horizontal vs Vertical Scaling







<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MDE3NDE2NywtMTkxMzU2NjQyMywzMj
MyMTExNzksMTY4MDAxNzgxMCwtMTUxODk5Nzg0OCw0MzQ3Njk1
MzAsMTAzOTgyMTIxOSwtMTE2MjMyNDk3NSwxODI4MzEyNDgzLC
0zMjYxNjc2MDMsMTQ5MjM1MjAwMyw2MzkyODY5OTgsLTE2Mzg3
Nzk2ODYsLTE4NzU1MzIwMSwtNTM5MTgwMzM4LDIwOTc5OTUyOD
UsMTkxMjI0ODQ4MywxMDUzODA4Njk4LC0xODc1NTQ4NzY4XX0=

-->