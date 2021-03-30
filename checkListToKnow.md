# Full Stack Web Developer
## Ms. Eng. Furkan Üzmez
if there is a star (*) in any subject you can write a blog post about it.
**bold item** -> have to know
normal item -> good to know (at least you should say "hear before") 
## Basics

### Data Structures *
- [x] **Array**
- [x] Linked List 
- [x] **Stack** 
- [x] **Queue** 
- [x] Binary Tree 
- [x] Binary Search Tree 
- [x] Heap 
- [ ] **Hashing** 
- [ ] Graph 
- [ ] Map, Dictionary

### Algorithms * 
- [ ] **Analysis of Algorithms**
- [ ] **Searching and Sorting**
- [ ] Greedy Algorithms
- [ ] Dynamic Programming
- [ ] Pattern Searching
- [ ] Backtracking
- [ ] **Divide and Conquer**
  
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
	- [x] **Adapter**
	- [ ] Bridge
	- [ ] Composite
	- [ ] **Decorator**
	- [ ] Facade
	- [ ] Flyweight
	- [ ] Proxy
 - [ ] Behavioral Patterns
	- [ ] Chain of Responsibility
	- [ ] Command
	- [ ] Interpreter
	- [ ] **Iterator**
	- [ ] Mediator
	- [ ] Memento
	- [x] **Observer**
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
-  Axios 
- [ ] Hoisting *
- [ ] Event Bubbling *
- [ ] Scope
- [ ] Prototype *
- [ ] **Shadow DOM** *
 #### Shadow DOM

Shadow DOM var olan herhangi bir DOM öğesinden oluşturulabilen kapsüllenmiş DOM nesnesidir. Shadow DOM’u oluşturan DOM öğesi  **ShadowHost**, kapsüllenmiş yeni öğe ise  **ShadowRoot**  olarak adlandırılır. Aşağıdaki JavaScript parçası Shadow DOM öğesinin nasıl oluşturulduğunu göstermektedir.
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
### Testing
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
- [x] Linked List 
- [x] **Stack** 
- [x] **Queue** 
- [x] Binary Tree 
- [x] Binary Search Tree 
- [x] Heap 
- [ ] **Hashing** 
- [ ] Graph 
- [ ] Map, Dictionary

### Algorithms * 
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
eyJoaXN0b3J5IjpbNzQ0NTA2OTA0LC02MzEwMjAyNjAsLTE4Mz
U1NDgwMzQsLTkyNjU3NzgxMSwxMDkwNjQ1NDIyLDEzODQxODMy
OTgsLTEwMTA4OTM5NTMsLTE0OTA5MTMzMDMsMTIxMjY4OTcwNS
wtMTkxMzU2NjQyMywzMjMyMTExNzksMTY4MDAxNzgxMCwtMTUx
ODk5Nzg0OCw0MzQ3Njk1MzAsMTAzOTgyMTIxOSwtMTE2MjMyND
k3NSwxODI4MzEyNDgzLC0zMjYxNjc2MDMsMTQ5MjM1MjAwMyw2
MzkyODY5OThdfQ==
-->