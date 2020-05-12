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
* Difference an Exception and an Error
* Checked vs Unchecked
  * RuntimeException
  * Exception
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

## OOP Principles
* Encapsulation
* Inheritance
* Abstraction
* Polymorphism
* overridding vs overloading

## Best practices & Design Patterns
* Choose composition over inheritance
* Understand each type of relationship between classes:
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

