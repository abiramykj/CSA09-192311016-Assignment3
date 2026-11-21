# Programming in Java – Assignment 3 (CO3)

## Assignment Overview

This repository contains the implementation of **Programming in Java – Assignment 3 (CO3)**. It demonstrates advanced Java programming concepts through seven practical tasks involving exception handling, resource management, multithreading, synchronization, inter-thread communication, deadlock prevention, and concurrent processing.

Each task is organized into separate folders containing Java source files, input data, expected outputs, design documents, and task-specific documentation.

## Student Details

| Detail | Information |
|---|---|
| Student Name | Abiramy K J |
| Register Number | 192311016 |
| Department | Artificial Intelligence and Data Science |
| Batch | 2024–2028 |
| Subject | Programming in Java |
| Assignment | Assignment 3 – CO3 |

## Technologies Used

- Java
- Object-Oriented Programming
- Exception Handling
- Java I/O and File Handling
- Multithreading
- Thread Synchronization
- Inter-Thread Communication
- ExecutorService Framework
- Callable and Future
- Concurrent Collections
- Visual Studio Code
- Git and GitHub

## Repository Structure

```text
CSA09-192311016-Assignment3/
│
├── Task01_ATMExceptionHandling/
│   ├── src/
│   ├── input/
│   ├── output/
│   ├── design/
│   └── README.md
│
├── Task02_UserDefinedExceptions/
│   ├── src/
│   ├── input/
│   ├── output/
│   ├── design/
│   └── README.md
│
├── Task03_ResourceSafety/
│   ├── src/
│   ├── input/
│   ├── output/
│   ├── design/
│   └── README.md
│
├── Task04_ThreadLifeCycle/
│   ├── src/
│   ├── input/
│   ├── output/
│   ├── design/
│   └── README.md
│
├── Task05_CinemaSeatBooking/
│   ├── src/
│   ├── input/
│   ├── output/
│   ├── design/
│   └── README.md
│
├── Task06_DeadlockAndCommunication/
│   ├── src/
│   ├── input/
│   ├── output/
│   ├── design/
│   └── README.md
│
├── Task07_ConcurrentResultProcessor/
│   ├── src/
│   ├── input/
│   ├── output/
│   ├── design/
│   └── README.md
│
└── README.md
```

## Task Descriptions

### Task 01 – ATM Exception Handling

Demonstrates exception handling in an ATM withdrawal application. It handles invalid input, invalid withdrawal amounts, insufficient balance, and file-related errors using appropriate exception-handling mechanisms.

**Concepts:** try-catch, multiple catch blocks, finally, built-in exceptions, file handling.

### Task 02 – User-Defined Exceptions

Demonstrates the creation and use of custom exception classes in a file-submission storage scenario. It explains exception propagation, checked exceptions, and exception chaining.

**Concepts:** Custom exceptions, checked exceptions, throws, exception propagation, getCause().

### Task 03 – Resource Safety

Demonstrates resource management while reading files. It compares manual resource closing with the try-with-resources statement and examines how resources are released when exceptions occur.

**Concepts:** BufferedReader, IOException, resource management, try-with-resources, debugging.

### Task 04 – Thread Creation and Life Cycle

Demonstrates creating and executing multiple threads using both the Thread class and the Runnable interface. It explores thread execution, thread status, and waiting for thread completion.

**Concepts:** Thread, Runnable, start(), run(), isAlive(), join(), sleep().

### Task 05 – Cinema Seat Booking

Demonstrates race conditions in a cinema seat-booking system where multiple users attempt to book the same seats concurrently. It compares unsynchronized execution with synchronized methods and synchronized blocks.

**Concepts:** Race conditions, critical sections, synchronization, synchronized methods, synchronized blocks.

### Task 06 – Deadlock and Inter-Thread Communication

Demonstrates producer-consumer communication using a bounded buffer and explores techniques for preventing deadlocks during shared-resource operations.

**Concepts:** wait(), notifyAll(), synchronized, producer-consumer problem, lock ordering, deadlock prevention.

### Task 07 – Concurrent Result Processor

Implements a concurrent file-processing system that processes 10,000 student result files using different thread-pool sizes. It handles missing and invalid files while collecting processing results.

**Concepts:** ExecutorService, Callable, Future, ConcurrentLinkedQueue, exception handling, thread pools, performance comparison.

## How to Compile and Run

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root directory.
4. Compile and execute the Java program for the required task.

Example – Task 01:

```powershell
javac Task01_ATMExceptionHandling\src\ATMWithdrawal.java
java -cp Task01_ATMExceptionHandling\src ATMWithdrawal
```

Example – Task 04:

```powershell
javac Task04_ThreadLifeCycle\src\*.java
java -cp Task04_ThreadLifeCycle\src ThreadLifeCycleDemo
```

Example – Task 07:

```powershell
javac Task07_ConcurrentResultProcessor\src\ResultProcessor.java
java -cp Task07_ConcurrentResultProcessor\src ResultProcessor
```

The same approach can be followed for the remaining tasks by using their respective source folders and main class names.

## Learning Outcomes

Through this assignment, the following learning outcomes are demonstrated:

- Applying appropriate exception-handling techniques in Java applications.
- Designing and implementing user-defined exceptions.
- Managing file resources safely and efficiently.
- Understanding thread creation and the thread life cycle.
- Identifying and preventing race conditions using synchronization.
- Implementing inter-thread communication using wait() and notifyAll().
- Understanding deadlocks and applying prevention techniques.
- Developing concurrent applications using Java concurrency utilities.
- Comparing concurrent processing performance with different thread-pool sizes.

## Conclusion

This assignment provides practical exposure to advanced Java programming concepts. The seven tasks demonstrate how Java handles exceptions, manages resources, supports multithreading, protects shared data, and performs concurrent operations.

The implementations strengthen the understanding of writing reliable, efficient, and maintainable Java applications.

---

**Repository:** Programming in Java – Assignment 3 (CO3)  
**Student:** Abiramy K J  
**Register Number:** 192311016