# Full Stack Web Developer
## Ms. Eng. Furkan Üzmez
if there is a star (*) in any subject you can write a blog post about it.
**bold item** -> have to know
normal item -> good to know (at least you should say "hear before") 
## Basics

### Data Structures *
- [ ] **Array**
-         Array Dimensions ,  Python has not Array type but list type could be used as Array in Python . 
-         Array functions , push , pop   
- [ ] Linked List 
- [ In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list. ] 

 ####    MajorDifferenceswithArray: Important
-   **Size:** Since data can only be stored in contiguous blocks of memory in an array, its size cannot be altered at runtime due to risk of overwriting over other data. However in a linked list, each node points to the next one such that data can exist at scattered (non-contiguous) addresses; this allows for a dynamic size which can change at runtime.
-   **Memory allocation:**  For arrays at compile time and at runtime for linked lists.
-   **Memory efficiency:**  For the same number of elements, linked lists use more memory as a reference to the next node is also stored along with the data. However, size flexibility in linked lists may make them use less memory overall; this is useful when there is uncertainty about size or there are large variations in the size of data elements; memory equivalent to the upper limit on the size has to be allocated (even if not all of it is being used) while using arrays, whereas linked lists can increase their sizes step-by-step proportionately to the amount of data.
-   **Execution time:** Any element in an array can be directly accessed with its index; however in case of a linked list, all the previous elements must be traversed to reach any element. Also, better cache locality in arrays (due to contiguous memory allocation) can significantly improve performance. As a result, some operations (such as modifying a certain element) are faster in arrays, while some other (such as inserting/deleting an element in the data) are faster in linked lists.

- [ ] **Stack** 
- [  In case of arrays and linked lists, these two allows programmers to insert and delete elements from any place within the list, i.e., from the beginning or the end or even from the middle also. But in computer programming and development, there may arise some situations where insertion and deletion require only at one end wither at the beginning or end of the list. The stack is a linear data structure, and all the insertion and deletion of its values are done in the same end which is called the _top_ of the stack. Let us suppose take the real-life example of a stack of plates or a pile of books etc. As the item in this form of data structure can be removed or added from the top only which means the last item to be added to the stack is the first item to be removed. So you can say that the stack follows the Last In First Out (LIFO) structure. ] 
- [ ] **Queue**
- [ ] Binary Tree
- [ ] Binary Search Tree
- [ ] Heap
- [ ] Hashing
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
- [ ] Graph Algoritms
- [ ] Randomized Algorithms

### Design Patterns * (only bold patterns are important, just learn the others names)
- [ ] **Creational Patterns**
	- [ ] Abstract Factory
	- [ ] Builder
	- [ ] **Factory Method**
	- [ ] Prototype
	- [ ] **Singleton**
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
eyJoaXN0b3J5IjpbNjM5Mjg2OTk4LC0xNjM4Nzc5Njg2LC0xOD
c1NTMyMDEsLTUzOTE4MDMzOCwyMDk3OTk1Mjg1LDE5MTIyNDg0
ODMsMTA1MzgwODY5OCwtMTg3NTU0ODc2OF19
-->