# Statistical Methods for Machine Learning: Homework Solutions

This repository contains solutions to the homework exercises for the course Statistical Methods for Machine Learning. The solutions are implemented in Jupyter Notebook. Below, we provide a summary of the tasks and how each one has been addressed.

## Direct Methods for the Solution of Linear Systems

## # Task 1: General Script

Given a matrix  and the vector , the following steps are performed:

Compute the Right-Hand Side:

Compute .

### Condition Number:

Compute the condition number of  using both the 2-norm and -norm.

Check if the matrix is ill-conditioned based on the condition numbers.

### Solve the Linear System:

Solve  using np.linalg.solve().

### Relative Error:

Compute the relative error between the computed solution  and the true solution :

### Graphs:

Plot the relative errors as a function of .

Plot the condition numbers in both norms as a function of .

Task 2: Testing with Different Matrices

The script is tested with the following matrices:

### Random Matrices:

Generate random matrices using np.random.rand() with .

### Vandermonde Matrices:

Use np.vander() with  and .

### Hilbert Matrices:

Use scipy.linalg.hilbert() with .

Floating Point Arithmetic

## Task 1: Machine Epsilon

Compute the machine epsilon  using a while loop until .

## Task 2: Euler Constant

Compute the sequence  for different values of .

Compare  with the true value of Euler's constant .

Analyze the behavior of  for large  and hypothesize the reason.

## Task 3: Matrix Properties

Matrices Definition:

Rank and Eigenvalues:

Compute the rank of  and  using np.linalg.matrix_rank().

Compute their eigenvalues using np.linalg.eigvals().

Full-Rank Condition:

Determine if  and  are full-rank matrices.

Analyze the relationship between eigenvalues and the full-rank condition.

Provide additional examples to support the deductions.

For more details, please refer to the full implementation in the accompanying Jupyter Notebook.
