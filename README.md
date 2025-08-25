# WriteHello Java Program

A simple Java program that demonstrates basic command-line argument usage by greeting a user with their name.

## Description

The `WriteHello` program is a basic Java application that takes a command-line argument and prints a personalized greeting message. This program is useful for learning fundamental Java concepts such as:

- Command-line argument handling
- Basic output using `System.out.println()`
- String concatenation

## Files

- `WriteHello.java` - Main Java source file containing the program logic

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE) to execute the program

## How to Compile

To compile the Java program, use the following command in your terminal:

```bash
javac WriteHello.java
```

This will create a `WriteHello.class` file in the same directory.

## How to Run

To run the program, use the `java` command followed by the class name and provide a name as an argument:

```bash
java WriteHello [Your Name]
```

### Example Usage

```bash
java WriteHello John
```

**Output:**
```
Hello John
```

```bash
java WriteHello "Alice Smith"
```

**Output:**
```
Hello Alice Smith
```

## Important Notes

- The program expects exactly one command-line argument (the name)
- If no argument is provided, the program will throw an `ArrayIndexOutOfBoundsException`
- To include spaces in the name, wrap it in quotes

## Learning Objectives

This program demonstrates:
1. Basic Java syntax and structure
2. Command-line argument processing using `args[]` array
3. String concatenation and output formatting
4. Compilation and execution of Java programs

## Author

Created for Capstone project demonstration.
