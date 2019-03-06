# Parallel-Triangular-Solve
MPI implementation of a solver for sparse triangular system. The solver uses huristic approach to exploit structure of the matrix and to achieve maximum parallelization. 

Input of the sparse system in compressed sparsed formate: 
> <strong>colp.dat</strong>: Contains Collumn pointer of the non-zero element of matrix
> <strong>rowi.dat</strong>: Contains Row Index of the non-zero element of the matrix
> <strong>val.dat</strong>:  Contains rhs values
  
For complete problem statment, algorithm used and the preliminary tests performed, please take a look at se294_projectReport.pdf
