# Unexpected Behavior with Pointers in C

This repository demonstrates a common, yet subtle, bug in C programming involving pointer arithmetic and memory management. The primary issue lies in the potential for incorrect pointer manipulation leading to unintended modification of variables.

## The Bug

The provided `bug.c` file contains a simple program that initializes an integer variable and then attempts to modify its value indirectly through a pointer. While seemingly straightforward, the code hides a potential pitfall that can cause unexpected behavior.  The issue is in how the pointer is used, specifically whether it is correctly pointing to a valid memory location and whether the operations performed on that memory location are safe and appropriate.

## The Solution

The `bugSolution.c` file offers a corrected version of the code, highlighting the best practices to avoid this kind of issue and ensure pointer safety.