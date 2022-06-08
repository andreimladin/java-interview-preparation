# Java Interview Preparation

## Internship

### Analytical thinking
* Logical questions

### Programming
* Anything around this topic depending on the candidate's education
* Basic Programming
  * What is a program? What structure does it have?
  * What is a variable?
  * What is a procedure/method?

## Junior

### Analytical thinking
* Logical questions
* Algorithms
  * Sort an array

## OOP Principles
* Encapsulation
* Inheritance
* Abstraction
* Polymorphism
* overridding vs overloading

## Java Fundamentals
* Main class
* Class Structure (Constructor, fields, methods)
* Access & Non-Access modifiers
* Statements (if, switch, for, while, do-while)
* Types (Primitives, Wrappers)

### Strings
* what is a String in java
* immutability (== vs equals)
* String pool

### Exceptions
* What is an Exception?
* Difference an Exception and an Error
* Checked vs Unchecked
  * RuntimeException
  * Exception
* Most common predefined exceptions: e.g. NullPointerException, FileNotFoundException
* try-catch-finally block
* throw new exception
* Method signature with throw exception
* Correct handling (higher in the application structure)
* Correct wrapping (don't lose the root cause in case of technical exceptions)
* Well-defined exception hierarchy (starting from base -> splitting in two: technical and business -> ending in concrete exception classes)

### Collections
* Lists
  * ArrayList vs LinkedList
* Sets
  * TreeSet vs HashSet
* Maps
  * TreeMap vs HashMap
* equals() & hashCode()

## SQL
### Database & Table Structure
* Define a database
* Define a table with different column types (integer -> varchar -> blob -> clob)
* Define a primare key
* Define an index

### Relationships
* Define Foreign Keys
* One-to-many
* Many-to-one
* Many-to-many

### Queries
* WHERE clause

### Update & Delete
* by using WHERE clause

### Drop table

## Frameworks
* Basic Knowledge about Spring

## Tools
* Git
  * How does git work?
    * Remote & local repo, and commit-based tracking
  * What is a commit?
  * Have you ever used a branching strategy? why is this useful?
  * What are the main operations in git?
    * clone ? pull ? commit ? push ?
  * Have you ever used stash? (nice to have)

* Maven
  * What is maven used for?
    * Build tool, dependency management, ...
  * Do you know the default lifecycle in maven?
    * clean -> compile -> install (search for the complete answer)
  * How many repos are used by maven? And when?
    * central, local & private (if one defined)
* Jenkins (Nice to know)
  * What is jenkins used for?
    * Scheduling/Triggering build jobs
    * Useful for CI/CD
    * Automating builds/deployments

# Higher Seniority Level

### Java I/O
* What is a Stream?
* Difference between an InputStream and a Reader
* Difference between an OutputStream and a Writer
* Types of Streams
* Paths
* File Operations

## Threads
* Thread vs Runnable
* Starting a Thread
* Syncing a thread
* synchronized blocks
* Synchronized collections
* What is a race condition?
* What is a deadlock?

## Best practices & Design Patterns
* Naming Conventions
* SOLID principles
* Choose composition over inheritance
* Understand each type of relationship between classes and when to use them:
  * Inheritance 
  * Aggregation
  * Asociation
  * Composition

### Design Patterns
* any developer MUST know about the most of the design patterns and be able to use a few of them
* mandatory design patterns:
  * Singleton
  * Builder
  * Factory method
  * Strategy

## SQL 
* Normalization (Splitting tables in multiple tables with relations between them)

### Queries
* inner, outer, left & right join
* order by
* group by

## Frameworks & Concepts
* IoC & DI: Spring Framework
  * How does Spring IoC Container work?
  * What is a bean?
  * Difference between @Component, @Controller, @Service & @Repository
  * What is a @Configuration class and when should we use it?
    * What about @Bean annotation?
  * How do we inject an object in Spring?
  * What is application.yml file used for?
  * How does the main class look like in Spring Boot app?
    * What about the project structure? 
* Persistance (JPA)
  * CrudRepository & JpaRepository
  * ORM: @Entity & @Table & @Column & @Id
* Security
  * Authentication & Authorization
  * Ways of authentication
    * Form-based
    * Basic Auth
    * Digest Auth (Nice to have)
    * OAuth2 (Nice to have)

## Containerisation
* Docker 
* Container orchestration
  * Docker Compose
  * Kubernetes
  * Openshift
  * Cloudfoundry

# Senior

## Cloud Solutions
* AWS
* Azure
* Google Cloud Platform
* Private Cloud

# Transactions
* ACID
* Rollback/Commit
