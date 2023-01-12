# CS475Lab0
### Goal: 
This lab reviews the fundamentals of project management in C including compiling, debugging, and testing programs. The projects in this class are difficult. Practicing these fundamentals will save you valuable time and effort when facing harder tasks.

### References:
* [Makefiles](https://makefiletutorial.com/)
* [Bash](https://ss64.com/bash/)

### Background:
Fermat's Little Theorem (FLT) is an axiom in number theory. It states that for some prime p, a^(p-1) % p = 1. Conversly, when a number n is not prime there (usually) exists some witness w for which w^(n-1) % n /= 1.

### Task:
Use the function *power_mod* as a primality test to identify the composite (not prime) numbers in the file *nums*. Do this without modifying the \*.c files, or by writting any additional C files.
*Hint:* 2 is a witness for all of the composite numbers in the file *nums*.

### Steps:
1. Add a target **FLT_DEBUG** to the Makefile which enables the debug message in *FLT.c*. 
2. Create a bash script which accepts a list of numbers as input and outputs **only** the composite numbers from the original list. Use **FLT** or **FLT_DEBUG** with a base of 2 to test if numbers are prime.
