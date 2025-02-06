# UseStatic Java Program

This repository contains a simple Java program that demonstrates the use of static variables and a static method.

## Program Description

The `UseStatic` class illustrates how static variables and methods work in Java. 

### Static Variables

- `a`: A static variable initialized with the value `3`.
- `b`: A static variable with no explicit initialization, so it defaults to `0`.

### Static Method

- `meth(int x)`: A static method that takes an integer `x` as an argument and prints the values of `x`, `a`, and `b`.

### Main Method

The `main` method calls the `meth` method with the argument `42`.

## Code

```java
class UseStatic {
    static int a = 3;
    static int b;

    static void meth(int x) {
        System.out.println("x = " + x);
        System.out.println("a = " + a);
        System.out.println("b = " + b);
    }

    public static void main(String[] args) {
        meth(42);
    }
}
