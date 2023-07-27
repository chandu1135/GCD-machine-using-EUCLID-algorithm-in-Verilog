# GCD-machine-using-EUCLID-algorithm-in-Verilog
GCD Machine Project
===================

This project implements a hardware GCD (Greatest Common Divisor) machine using Verilog. The GCD machine is designed based on Euclid's algorithm to calculate the GCD of two input numbers.

Euclid's Algorithm for GCD
--------------------------
Euclid's algorithm is an ancient and efficient method for finding the GCD of two numbers. The algorithm is based on the observation that the GCD of two numbers does not change if the smaller number is subtracted from the larger number repeatedly. The process is repeated until both numbers become equal, which is the GCD of the original two numbers.

For example, to find the GCD of two numbers A and B:
1. If A = 0, then GCD(A, B) = B.
2. If B = 0, then GCD(A, B) = A.
3. Otherwise, repeatedly subtract the smaller number from the larger number.
4. Replace the larger number with the result of the subtraction, and the smaller number with the value of the original larger number.
5. Repeat steps 1-4 until both numbers become equal. The common value is the GCD of A and B.
