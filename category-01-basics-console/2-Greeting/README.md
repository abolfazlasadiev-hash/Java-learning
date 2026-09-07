# Greeting

A simple Java console program that asks the user for their name and displays a personalized greeting.

##  Goal

The goal of this project is to learn how to:

* Get text input from the user
* Store text in a `String` variable
* Use `Scanner`
* Combine strings using `+`
* Display output in the console

##  Concepts

### 1. Scanner

`Scanner` allows the program to read input from the keyboard.

```java
Scanner scanner = new Scanner(System.in);
```

### 2. String

A `String` stores text.

```java
String name = "Sara";
```

### 3. nextLine()

`nextLine()` reads a complete line entered by the user.

```java
String name = scanner.nextLine();
```

### 4. String Concatenation

The `+` operator can combine strings and variables.

```java
System.out.println("Hello, " + name);
```

### 5. Console Output

`System.out.print()` and `System.out.println()` display information in the console.

##  How to Run

Save the file as:

```text
Greeting.java
```

Compile:

```bash
javac Greeting.java
```

Run:

```bash
java Greeting
```

##  Example

```text
Enter your name: Sara
Hello, Sara! Welcome to Java programming.
```

## What I Learned

After completing this project, I should understand:

* How to create a basic Java program
* How to use `Scanner`
* How to read user input
* How to use `String`
* How to concatenate strings
* How to display personalized output

## 🔑 Main Java Concepts

`Scanner` • `String` • `nextLine()` • `System.out.print()` • `System.out.println()` • String concatenation
