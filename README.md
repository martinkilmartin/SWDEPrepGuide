# Software Development Engineer Knowledge Guide

## Coding
### Algorithms
 * Runtimes (Big O Notation)
   * O(1)       constant-time
   * O(log n)   logarithmic
   * O(n)       linear
   * O(n log n) log linear
   * O(n^2)     quadratic
   * O(n^3)     cubic
   * O(2^n)     exponential
   * O(n!)      factorial
 * Space complexity 
 * Theoretical Limitations
 * Sorting
 * Searching
 * Tree Traversal
   * Pre-Order
   * In-Order
   * Post-Order
 * Tree Search 
   * Breadth First Search
   * Depth First Search
 * Recursion
 * Divide & Conquer
 * Memoization
### Data Structures
 * Common Operation Runtime
   * Insert
   * Seek
   * Delete
 * Memory Usage
 * Array
 * Vector
 * Map
 * Set
 * Hash Table
 * Hash Map
 * Stack
 * Queue
 * Graph
   * **Everything** is a graph.
 * Tree
   * DOM
 * Heap
### Testing

### Debugging 

### DevOps

## Scripting & Regular Expressions
* Unix
* grep
* sed
* awk
* bash
* perl
* python
* Ruby

## Bits & Bytes
* Integer-overflow
* Logical operations
  * && AND
  * || OR
  * !  NOT
* Bitwise operatorions
  * & AND
  * | OR
  * ^ XOR
* Bitwise shift operations
  * <<  Left
  * \>\>  Right
  * \>\>\> Unsigned Right
* Primitive types
  * byte
  * short
  * int
  * long
  * float
  * double
  * char
  * boolean
* Signed vs. unsigned types
* Most (Least) significant bit / high(low)-order bit / left(right)-most bit
  * Two's complement / Signed Binary Numberp

### Versioning
* Version Control System (VCS) | Software Configuration Management (SCM)
** Git

## Object Orientated Design
* Design Patterns
  * Creational Patterns
    * Abstract Factory
    * Factory Method
    * Builder
    * Prototype 
    * Singleton
  * Structural Patterns
    * Adapter
    * Bridge
    * Composite
    * Decorator
    * Facade
    * Flyweight
    * Proxy
  * Behavioural Patterns
    * Chain of Responsibility
    * Command
    * Interpreter
    * Iterator
    * Mediator
    * Memento
    * Observer
    * State
    * Strategy
    * Template
    * Visitor
* Inheritence
  * Relating classes so they may use another class's members without redefining them.
* Composition
  * Creating complex types by combining objects of other types modelling a **has a** relationship.
* Aggregation
  * Association between objects where each object has its own life cycle but an ownership exists as well.
* Class vs. Object
  * Blueprint vs. Instance 
* Instantiation
* Java method vs. C function
* Virtual method vs. Pure virtual method
* Static method
* Static Class initializer
* Constructor
* Destructor / finalizer
* Superclass / base class
* Subclass / derived class
* Encapsulation
* Multiple inheritance 
* Delegation / forwarding
* Abstract class
  * An abstract class is a class that cannot be instantiated. We create abstract classes to provide a common template for other classes to extend and use. An abstract class may contain both abstract and non-abstract properties and functions.
* Interface / protocol
* Method overriding
* Method overloading
* Polymorphism 
* is-a versus has-a relationships
* Method signatures
* Method visibility
  * private
  * default
  * protected
  * public

## Functional Programming
* λ-calculus
* Higher-Order functions
  * Take function(s) as argument(s) or return function(s).
* Pure functions
  * avoid:
    * shared state
    * mutable data
    * side-effects
* First-Class functions 
* Immutability 

## System Design
* Requirements Clarification
  
| Users / Customers | Scale (reads / writes) | Performance | Cost |
| --- | --- | --- | --- | --- |

| Functional Requirements | Non-Functional Requirements  |
| --- | --- | --- | --- | --- |

* Ingestion Components

| Partitioner Service Client | Load Balancer | Partitioner Service and Partitions |
| --- | --- | --- |
| Blocking v non-blocking I/O | Software v hardware load balancing | Partition strategy |
| Buffering and batching | Network Protocols | Service discovery |
| Timeouts | Load balancing algorithms | Replication |
| Retries | DNS | Message Format |
| Exponential back-off and jitter | Health checking | |
| Circuit breaker | High availability | |

* Service Orientated Architecture
* Caching
  * Memcached
  * Redis (Remote Dictionary Server)
    * In-Memory DataBase that persists on disk with a key-value data model supporting many different types of values such as Strings, Lists, Sets, Sorted Sets, Hashes, Streams, HyperLogLogs and Bitmaps.
* N-Tiered Architecture
* Message Broker
  * RabbitMQ
* Container-Orchestration
  * Kubernetes

## Operating Systems
* Memory Management
* Synchronization
* Paging
* Multithreading

## Databases
* Relational
  * PostgreSQL
  * MySQL
  * SQLite
* Non-Relational
  * **Document Database**
    * Stores data in JSON, BSON , or XML documents
    * Use cases include ecommerce platforms, trading platforms, and mobile app development across industries.
  * **Key-Value Store**
    * Use cases include shopping carts, user preferences, and user profiles.
  * **Column-Oriented Databases**
    * Use cases include analytics.
  * **Graph Databases**
    * A graph database is optimized to capture and search the connections between data elements, overcoming the overhead associated with JOINing multiple tables in SQL.
    * Use cases include fraud detection, social networks, and knowledge graphs.
  * MongoDB
    * Document orientated database that uses leader-based replication
  * Cassandra
    * Wide column database that supports asynchronous master replication
    * Fault tolerant
    * Linear Scalability
    * Multi-Data-center replication
  * Apache HBase
    * Wide column database that supports master replication
    * Linear and modular scalability.
    * Strictly consistent reads and writes.
    * Automatic and configurable sharding of tables.
    * Automatic failover support between RegionServers.
  * AWS Dynamo
    * Key-value and document database
    * Delivers single-digit millisecond performance at any scale.
    * In-memory caching for internet-scale applications.
  * AWS ElastiCache
  * Google Cloud Datastore
* Partitioning
* Replication
* Sharding
* CAP Theorem
  * Computer scientist Eric Brewer, states that it is impossible for a distributed data store to simultaneously provide more than two out of the following three guarantees:
    * **Consistency**: Every read receives the most recent write or an error
    * **Availability**: Every request receives a (non-error) response, without the guarantee that it contains the most recent write
    * **Partition tolerance**: The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes

## Architecture
* Scalability
* Concurrency
  * Threads
  * Deadlock
  * Starvation
  * Consistency
  * Coherence

## Networking
* IPC
* TCP/IP
* UDP
* DNS

## Real-world performance
* Relative performance RAM
* Disk
* Network
* SSD

## Availability & Reliability
* Failure types
* Failure units
* Failure manifestation
* Failure mitigations

## Data Storage & Aggregation

## QPS capacity / Machine Estimation

## Distributed Systems
* Workflow Systems
* Map-Reduce
* Distributed Caching Systems
* Load Balancing
* Event Streaming
  * Apache Kafka

## Client Development
* Accessibility
* UX
* Graphics Libraries
* Computational Geometry
* Hardware Integration
* Content Protection Schemes
* System Development Kit (SDK) Design

## Web
* Accessibility
* UX
* SEO
* Reusable Components
* Application State Management
* HTML5
* CSS
* Javascript
  * Iteration
  * Closures
  * Scope
  * Asynchronous Code
* Typescript
* JSON
* REpresentational State Transfer
* Resource Caching
* Content Delivery
* Asynchronous Programming
* Real User Metrics
* Client v Server Rendering
* Browser / Devide Rendering Efficiency
* Data FLows
* Operational Performance
  * Acceptable Performance Levels
  * Troubleshooting
  * Points Of Failure & Mitigation
* Devices
  * System Availability
  * Efficient Resource Usage
  * Performance Implications
  * Security
* Browsers
  * Native API Methods
  * Local Storage
  * Compatability
  * Progressive Web Apps
* Security
  * Web Security model
    * Same-origin policy
    * Cross-origin resource sharing
    * Content Security Policy
    * Hashes and nonces
    * Subresource integrity
  * Client vs. server security
    * Client-side security
    * Server-side security
    * HTTPS Communication
    * Tokens vs. sessions
  * Security vulnerabilities
    * OWASP Top 10
    * Cross-site scripting
    * Cross-site request forgery
    * JWT Hacking
  * Application architecure
    * Role-based access control design
    * Application architecure
    * Authentication vs. Authorization
    * Secured API
    * Router Guards
    * Http Interceptors
  * Client security implementation
    * Content Security Policy
    * XSS prevention
    * CSRF prevention
    * HttpOnly Cookies
      * Set-Cookie HTTP response header that helps mitigate the risk of client side script accessing the protected cookie (if the browser supports it).
    * Secure Cookies
    * UserAuth object
    * Conditional components visibility
  * API security implementation
    * Sever-side session
    * Logging access and application events
    * Throttling failed logins
    * Input sanitization and validation
    * Two vectors of authorization
    * Preventing unauthorized requests
    * CORS
  * Roles and account management
    * Adding new user accounts
    * Confirming new user accounts
    * Password recovery
    * Managing active sessions
    * Removing logged users
  * External authentication
    * OAuth 2.0
    * Authorization Code Flow + PKCE
    * Id Token vs. Access Token
    * OpenID Connect (OIDC)
  * Multi-factor authentication
    * One-time password (OTP)
  * External user management
    * Federated identity management (FIM)
    * Single sign-on (SSO)
    * IDaaS - Identity as a Service
