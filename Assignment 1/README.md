# Assignement 1 

## Objective
The objective of this assignment is to write a C function ``` compute_stats() ``` that calls an ARMv7-M 

assembly language function ``` asm_stats() ``` to compute the fundamental statistical parameters

min, max, mean and variance.

All the data values are assumed to be integers which can be positive, zero 

or negative (with values between -100 and +100 inclusive), and the computed statistical parameters only need to be accurate to

the nearest integer value and should be passed back to the C function ``` compute_stats() ``` which calls

the ``` asm_stats() ``` function.