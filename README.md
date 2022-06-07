# Java Interview Preparation

## Internship

### Analytical thinking
* Logic questions

### Programming
* Anything around this topic depending on the candidate's education
* Basic Programming
  * What is a program? What structure does it have?
  * What is a variable?
  * What is a procedure/method?

## Junior

### Analytical thinking
* Logic questions
* Algorithms
** Sort an array

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
* String pool
* == vs equals

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
* Maven
* Jenkins (Nice to know)

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
* Normalization

### Queries
* inner, outer, left & right join
* order by
* group by

## Frameworks & Concepts
* IoC & DI: Spring Framework
* Persistance (JPA)
* Security
  * Authentication & Authorization
  * Ways of authentication
    * Form-based
    * Basic Auth
    * Digest Auth (Nice to have)
    * OAuth2 (Nice to have)

# Senior

## Containerisation
* Docker 
* Container orchestration
  * Docker Compose
  * Kubernetes
  * Openshift
  * Cloudfoundry

## Cloud Solutions
* AWS
* Azure
* Google Cloud Platform
* Private Cloud

# Transactions
* ACID
* Rollback/Commit
