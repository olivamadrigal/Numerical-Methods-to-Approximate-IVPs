# Numerical-Methods-to-Approximate-IVPs 

# ABOUT # 
Numerical Methods to Approximate Initial Value Problems. 

In the given sample live script, Euler's Method (Taylor Order One), Taylor's Method Order 2, and Runge-Kutta Method Order 4, are called to approximate the solution the differential equation:   y'(t) = 2y = e^t  for  0 <= t <= 3  with initial condition of y(0) = 1. 

The specified value of the time-step h is 0.1. 

# HOW TO TEST IT #
source.m contains all source code to fork. Algorithms implemented were tested using MATLAB_R2017a.

1) From the source.m, create separate a matlab (.m) script for each algorithm with filename as that of the algorithm.

2) Create a live script with the live script code provided to test the solution to the IVP above. To test other equations, replace
variable f with the differential equation in single quotes to be passed as a string; replace variable f1 with the derivate of the differential equation. The later is required for Taylor Order 2 method. 

# RESULTS #

results.pdf shows results of the approximationts at each mesh point up to the approximated solution as well a graph of the approximation using each method.

