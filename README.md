# torus
A fourth degree equation solver

USAGE

./105torus opt a0 a1 a2 a3 a4 n

DESCRIPTION

opt     method option:
          1 for the bisection method
          2 for Newton's method
          3 for secant method
a[0-4]  coefficients of the equation
n       precision (the application of the polynomial to the solution should\n\t\tbe smaller than 10^-n)
