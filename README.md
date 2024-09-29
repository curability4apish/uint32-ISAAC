# Why 4B-ISAAC
```
/* a ub4 is an unsigned 4-byte quantity */
typedef  unsigned long int  ub4;
```
Unsigned long int is treated as 8-byte by some compilers, potentially causing inconsistent results across different IDEs.

This repository aims to solve the issue by force configuration of unsigned quantity to 4-byte.

For experimental purpose, you may use 8B version as well.

