# Division by Zero in C
This repository demonstrates a common error in C programming: division by zero. The `bug.c` file contains the erroneous code, while `bugSolution.c` provides a corrected version.

**The Bug:**
The program attempts to divide an integer `a` by an integer `b`, where `b` is 0. This results in undefined behavior, potentially causing a program crash or unexpected output.

**The Solution:**
The solution adds a check to ensure that the divisor `b` is not zero before performing the division. This prevents the program from crashing and provides a more robust solution.