# Why
```
/* a ub4 is an unsigned 4-byte quantity */
typedef  unsigned long int  ub4;
```
[unsigned long int](https://burtleburtle.net/bob/c/readable.c) is treated as 8-byte by some compilers, potentially causing inconsistent results across different IDEs.

This repository aims to solve the issue with the use of uint32_t to represent 4-byte quantity.

For experimental purposes, you may use uint64 version as well.

