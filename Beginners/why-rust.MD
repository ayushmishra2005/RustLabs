---
layout: default
title:  Why Rust?
parent: Rust for Beginners
nav_order: 1
---

# Why Rust?

What makes Rust important?

- Why Is Rust Different? <br>
      -  Speed <br>
      - Safety <br>
      -  Cargo Manager <br>
      - Error Messages <br>
      - Efficient C Binding <br>
      - Threads without Data Races <br>


# Why Is Rust Different? 

There are many reasons why Rust is different from other programming languages.

# Speed 

Rust pays no penalty for the abstraction and only pays for the features that are actually used. This improves 
the code quality and readability without affecting the run time cost.

# Safety 

Rust does not have a garbage collector. It ensures memory safety using ownership and its borrowing concept 
The most significant difference between C, C++, and Rust is writing safe code. 
In Rust, the objects are managed by the programming language from the beginning to the end. The proper amount of memory required is allocated
and automatically deallocated by the system when it is no longer in use.


# Cargo Manager 

System languages like C and C++ never had a standard package manager. Rust provides a cargo manager that has all the
rust libraries and frameworks to not only help developers make fantastic applications, but also distribute code to end-users.

# Error Messages 

The error messages in Rust are displayed using color. Formatting and misspellings in the program are commonly suggested.
It not only displays the line which has the error but, also the type of error.

# Efficient C Binding 

The Rust language can interoperate with the C language. It provides a foreign function interface to communicate with C API’s. 
Due to its ownership rules, it can guarantee memory safety.


# Threads without Data Races 

Data race is a condition where two or more threads can access the same memory location. Rust uses the concept of ownership to avoid data races.





