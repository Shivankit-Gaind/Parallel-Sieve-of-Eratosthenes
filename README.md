# Parallel-Sieve-of-Eratosthenes


The repository contains solution to one of the assignments of the course Parallel Computing in BITS Pilani.

The problem statement is described as follows:

A. Design a parallel version of the Sieve of Eratosthenes algorithm given below to find all primes less than N (an input integer):
1. Create the list Nums of numbers from 2 to N;
2. Initially no number is crossed out.
3. Let pr=2;
4. Scan Nums from the left and cross out multiples of pr (except pr itself).
5. Update pr to be the next number not crossed out (to the right of current pr).
6. Repeat steps 4) and 5) until pr > sqrt(N)

B. Implement this parallel algorithm using MPI in C. Note that your program should be parameterized by N, the input, and p, the number of nodes available.

C. Measure the performance for different values of N in the range 10^5 to 10^10. For each value of N, measure the performance for p = 1, 2, 4, and 8 where p is the number of (physical) nodes used and plot a curve indicating how performance (of a single input) varies as p increases.

The design, measurements and inferences are summarized in the design document.
