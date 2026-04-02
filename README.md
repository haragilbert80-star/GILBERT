Pointer Concepts in C++
 Overview
This repository is a collection of educational examples demonstrating how pointers work in C++. Each program highlights a specific aspect of pointer usage, function calls, and memory handling. The goal is to provide clear, practical demonstrations of fundamental concepts for students and learners of C++ programming.

 Topics Covered
 
Pointer Arithmetic  
How incrementing or decrementing a pointer moves it by the size of the data type it points to.

Pointer Arithmetic with char  
Demonstrates how pointer movement differs with smaller data types (1 byte for char).

Printing Variables and Addresses  
Shows how to print both the value of a variable and its memory address.

Arrays and Pointers  
Explains the close relationship between arrays and pointers, showing that arr[index] and ptr[index] are interchangeable.

Negative Indexing with Pointers  
Demonstrates that pointer arithmetic supports both positive and negative offsets.

Modifying Arrays with Functions  
Illustrates how arrays can be modified inside functions since they are passed by reference.

Array Indexing vs Pointer Arithmetic  
Shows that arr[index] is equivalent to *(arr + index).

Function Calls and Addresses  
Explains that functions themselves have memory addresses, which can be printed and manipulated.

Function Pointers  
Demonstrates declaring, assigning, and calling functions via pointers.

Function Pointers with Multiple Functions  
Shows how to pass function pointers as arguments to achieve dynamic function selection.

Returning Function Pointers  
Illustrates how a function can return another function’s pointer, enabling runtime selection.

Pointer to Constant  
Explains how pointers to constant data prevent modification through dereferencing.

Constant Pointer  
Shows how constant pointers cannot be redirected to another variable but can modify the value they point to.

Constant Pointer to Constant Data  
Demonstrates strict immutability: neither the pointer nor the data can be changed.

Pointer Dereference  
Highlights the difference between printing a pointer’s address and dereferencing it to access the stored value.

Call by Value  
Explains how passing arguments by value creates copies, leaving original variables unchanged.

Void Pointers  
Introduces generic pointers that can point to any data type but require casting before dereferencing.

Purpose

This repository is designed as a learning resource for students and developers who want to:

Understand the fundamentals of pointers in C++.

Explore practical examples of pointer arithmetic, function pointers, and const correctness.

Strengthen their grasp of memory management and function calling mechanisms.
