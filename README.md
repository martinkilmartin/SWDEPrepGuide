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
 * Graph / Tree Traversals
   * Breadth First Search
   * Depth First Search
 * Sorting
 * Searching
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
 * DOM Tree
 * Hash Table
 * Hash Map
 * Stack
 * Queue
 * Graph
 * Tree
 * Heap

## Object Orientated Design
* Common Design Patterns
* Inheritence
* Composition
* Aggregation
* Class v. Object
* Instantiation
* Java method v. C function
* Virtual method v Pure virtual method
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
* Pure functions 
* First-Class functions 
* Immutability 

## System Design
* Service Orientated Architecture
* Caching
  * Memcached
  * Redis (Remote Dictionary Server)
    * In-Memory DataBase that persists on disk with a key-value data model supporting many different types of values such as Strings, Lists, Sets, Sorted Sets, Hashes, Streams, HyperLogLogs and Bitmaps.
* N-Tiered Architecture

## Operating Systems
* Memory Management
* Synchronization
* Paging
* Multithreading

## Databases
* Relational v Non-Relational
* Partitioning
* Replication
* Sharding
* CAP Theorem

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

## Client Development
* Graphics Libraries
* Computational Geometry
* Hardware Integration
* Content Protection Schemes
* System Development Kit (SDK) Design

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
  * Two's complement / Signed Binary Number

## Web
* Reusable Components
* Application State Management
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
    * Setting up 2FA
    * Requesting one-time password (OTP)
    * Validating one-time password (OTP)
  * External user management
    * Federated identity management (FIM)
    * Single sign-on (SSO)
    * IDaaS - Identity as a Service
