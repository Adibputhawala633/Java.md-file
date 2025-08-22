# Java.md-file
Give basic Java Notes that help to learn

# Java Notes

## Introduction

Java is a high-level, class-based, object-oriented programming language
designed to have as few implementation dependencies as possible. It is
widely used for building platform-independent applications.

------------------------------------------------------------------------

## Features of Java

-   **Platform Independent**: Write once, run anywhere.
-   **Object-Oriented**: Everything in Java is treated as an object.
-   **Robust**: Strong memory management, exception handling, and type
    checking.
-   **Secure**: Provides a secure environment by avoiding explicit
    pointers and running programs inside JVM.
-   **Multithreaded**: Allows the development of multithreaded programs
    for better CPU utilization.

------------------------------------------------------------------------

## Basic Structure of a Java Program

``` java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

------------------------------------------------------------------------

## OOP Principles in Java

1.  **Encapsulation**: Wrapping variables and methods in a class.
2.  **Inheritance**: One class can inherit fields and methods from
    another.
3.  **Polymorphism**: Ability to perform a single action in different
    ways.
4.  **Abstraction**: Hiding implementation details and showing only the
    functionality.

------------------------------------------------------------------------

## Commonly Used Java Concepts

-   **JVM (Java Virtual Machine)**: Executes Java bytecode.
-   **JDK (Java Development Kit)**: Contains tools for Java development.
-   **JRE (Java Runtime Environment)**: Provides libraries and JVM for
    running programs.

------------------------------------------------------------------------

## Example: Class and Object

``` java
class Car {
    String color;
    int speed;

    void drive() {
        System.out.println("The car is driving at " + speed + " km/h");
    }
}

public class Main {
    public static void main(String[] args) {
        Car myCar = new Car();
        myCar.color = "Red";
        myCar.speed = 120;
        myCar.drive();
    }
}
```

------------------------------------------------------------------------

## Conclusion

Java remains one of the most widely used programming languages for
developing cross-platform applications, enterprise software, and mobile
applications (Android).
