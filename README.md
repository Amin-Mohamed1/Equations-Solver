# Equations Solver

A comprehensive set of algorithms for solving linear and non-linear equations, implemented in Java and Python.

## Linear Equations Solver in Java

### 1. **Gauss Elimination**
   - A direct method for solving linear systems by transforming the matrix into an upper triangular form and then performing back substitution.

### 2. **Gauss-Jordan Elimination**
   - An extension of Gauss Elimination that transforms the matrix into reduced row echelon form, providing the solution directly.

### 3. **LU Decomposition**
   - Decomposes a matrix into the product of a lower triangular matrix (L) and an upper triangular matrix (U), facilitating easier solution of linear systems.

   - **Dolittle Method**
     - Produces a unit lower triangular matrix (L) and an upper triangular matrix (U).

   - **Crout Method**
     - Produces a lower triangular matrix with non-zero diagonal elements (L) and an upper triangular matrix (U) with unit diagonal elements.

   - **Cholesky Decomposition**
     - Special case for symmetric positive-definite matrices, decomposing the matrix into the product of a lower triangular matrix and its transpose.

### 4. **Gauss-Seidel Method**
   - An iterative technique for solving a system of linear equations, useful for large systems where direct methods are inefficient.

### 5. **Jacobi Iteration**
   - Another iterative method for solving linear equations, suitable for systems with diagonally dominant matrices.

## Non-Linear Equations Solver in Python

### 1. **Bisection Method**
   - A simple and robust method for finding a root of a function by repeatedly dividing the interval and selecting the subinterval in which the function changes sign.

### 2. **False Position (Regula Falsi) Method**
   - An improvement over the bisection method that uses a secant line to approximate the root, converging faster.

### 3. **Fixed Point Iteration**
   - An iterative method where a function is rearranged so that finding a fixed point corresponds to finding a root.

### 4. **Original Newton-Raphson Method**
   - A powerful method for finding roots of a real-valued function, using the function's derivative to achieve quadratic convergence.

### 5. **Modified Newton-Raphson Method**
   - A variation of the original method that includes modifications to handle cases where the derivative is small or the initial guess is far from the root.

### 6. **Secant Method**
   - An iterative method similar to Newton-Raphson, but does not require the calculation of derivatives, using secant lines instead.
