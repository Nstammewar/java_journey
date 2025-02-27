# Java Concepts Blog Structure

## Table of Contents

### [1. Java Fundamentals](/java-fundamentals.md)
- [Java Syntax Basics](/java-fundamentals/syntax-basics.md)
- [Variables and Data Types](/java-fundamentals/variables-data-types.md)
- [Operators](/java-fundamentals/operators.md)
- [Control Flow](/java-fundamentals/control-flow.md)
- [Arrays and Strings](/java-fundamentals/arrays-strings.md)
- [Packages and Imports](/java-fundamentals/packages-imports.md)
- [Comments and Documentation](/java-fundamentals/comments-documentation.md)

### [2. Object-Oriented Programming (OOP)](/oop.md)
- [Classes and Objects](/oop/classes-objects.md)
- [Constructors and Methods](/oop/constructors-methods.md)
- [Inheritance](/oop/inheritance.md)
- [Polymorphism](/oop/polymorphism.md)
- [Abstraction](/oop/abstraction.md)
- [Encapsulation](/oop/encapsulation.md)
- [Interfaces vs. Abstract Classes](/oop/interfaces-vs-abstract-classes.md)
- [Composition vs. Inheritance](/oop/composition-vs-inheritance.md)
- [static Keyword](/oop/static-keyword.md)
- [final Keyword](/oop/final-keyword.md)

### [3. Data Structures & Collections](/collections-framework.md)
- [Introduction to Collections](/collections-framework/intro-collections.md)
- [Lists (ArrayList, LinkedList)](/collections-framework/lists.md)
- [Sets (HashSet, TreeSet)](/collections-framework/sets.md)
- [Maps (HashMap, TreeMap)](/collections-framework/maps.md)
- [Queues and Deques](/collections-framework/queues-deques.md)
- [Iterators and Comparators](/collections-framework/iterators-comparators.md)
- [Sorting and Searching](/collections-framework/sorting-searching.md)
- [Java Stream API](/collections-framework/stream-api.md)

### [4. Exception Handling](/exception-handling.md)
- [Try-Catch Blocks](/exception-handling/try-catch.md)
- [Checked vs. Unchecked Exceptions](/exception-handling/checked-unchecked.md)
- [Custom Exceptions](/exception-handling/custom-exceptions.md)
- [throws and throw Keywords](/exception-handling/throws-throw.md)
- [Finally Block](/exception-handling/finally-block.md)
- [Try-with-Resources](/exception-handling/try-with-resources.md)

### [5. Input/Output (I/O)](/io-operations.md)
- [File Handling](/io-operations/file-handling.md)
- [Byte Streams](/io-operations/byte-streams.md)
- [Character Streams](/io-operations/character-streams.md)
- [Buffered Streams](/io-operations/buffered-streams.md)
- [Serialization/Deserialization](/io-operations/serialization.md)
- [NIO Package](/io-operations/nio.md)

### [6. Concurrency & Multithreading](/concurrency.md)
- [Thread Lifecycle](/concurrency/thread-lifecycle.md)
- [Creating Threads](/concurrency/creating-threads.md)
- [Synchronization](/concurrency/synchronization.md)
- [Thread Pools](/concurrency/thread-pools.md)
- [Callable and Future](/concurrency/callable-future.md)
- [Concurrent Collections](/concurrency/concurrent-collections.md)
- [Deadlocks and Race Conditions](/concurrency/deadlocks-race-conditions.md)
- [Java Memory Model (JMM)](/concurrency/java-memory-model.md)

... (Continue similarly for other sections)

---

### Example of a Subsection File (`/java-fundamentals/syntax-basics.md`):
```markdown
# Java Syntax Basics

Java syntax is the set of rules defining how a Java program is written. Key components include:

- **Case Sensitivity**: `MyClass` ≠ `myclass`.
- **Class Names**: Start with uppercase (e.g., `Main`).
- **Method Names**: Start with lowercase (e.g., `printMessage()`).
- **Main Method**: Entry point: `public static void main(String[] args)`.

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
