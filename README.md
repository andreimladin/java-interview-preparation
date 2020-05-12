# Java Interview Preparation

## Java Fundamentals

### Main class
* the entry method in Java
* the signature of the main method

### Class Structure
* Constructor
* Variables 
  * Constants
  * Instance variable
  * Local variable
* Methods
  * Signature (parameters & return type)
  
### Access modifiers
* private
* default
* protected
* public

### Non-Access modifiers
* static
* final
* volatile

### Statements
* If-then-else
* switch
* for
* while
* do-while
* Ternary operator

### Primitives
* integer types
  * byte
  * short
  * int
  * long
* float types
  * float
  * double
* char
* boolean

## Strings
* what is a String in java
* String pool
* == vs equals

## Exception
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

## Collections
* Lists
  * ArrayList vs LinkedList
* Sets
  * TreeSet vs HashSet
* Maps
  * TreeMap vs HashMap
* equals() & hashCode()

## Java I/O
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

## OOP Principles
* Encapsulation
* Inheritance
* Abstraction
* Polymorphism
* overridding vs overloading

## Best practices & Design Patterns
* Naming Conventions
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

### Normalization

### Queries
* WHERE clause
* inner, outer, left & right join
* order by
* group by

### Update & Delete

### Drop table
