# data_analysis_and_data_science_with_python

MTH343 Projections, Subspaces, Orthogonality, and QR Decomposition:

Note: This project is listed in my CV as "**Digit Classification via Least Squares and QR Decomposition**".

-Explored orthogonality and how to use it in order to describe matrices and solve least squares.

-Used least squares and QR in order to try and classify handwritten digits from the MNIST dataset.

-Improved the least squares classifier by implementing it as a binary classifier, took a vector for each category then used the matrices Q and R to solve the least squares problem for x for each of these vectors. In the end, got a resulting prediction, compared the predicted labels with the actual labels, and calculated the prediction accuracy.

MATH343_Stationary_Methods_for_Solving_Positive_Definite_Systems_Homework_5:

Note: This project is listed in my CV as "**Iterative Methods for Sparse Linear Systems**".

-Developed L1, Forward Gauss-Seidel, and Symmetric Gauss-Seidel solvers for SPD systems; evaluated convergence via residual norm plots.

-Implemented Arnoldi iteration to generate orthonormal Krylov bases and approximate matrix eigenvalues.

-Extended Arnoldi to build a custom GMRES solver for non-symmetric systems with tolerance-based stopping criteria.

-Visualized spectral convergence by comparing Hessenberg and full matrix eigenvalues across iterations.

-Assessed algorithm performance across sparse matrices of varying size and condition number.

MTH343_Sparse_Matrices,_Symmetric_Matrices,_and_Relations_Graphs_Homework_2:

Note: This project is listed in my CV as "**Sparse Matrices, Graphs, and CSR-Based Linear System Solving**".

-Represented graph relationships (e.g., student-class enrollment) as sparse adjacency matrices using COO and CSR formats.

-Implemented conversions between dense and sparse formats and verified accuracy via norm checks and SciPy equivalence.

-Explored matrix relationships via AATA A^TAAT (student-student) and ATAA^T AATA (class-class) to uncover co-enrollment patterns.

-Solved upper-triangular linear systems in CSR format using custom back substitution without converting to dense.

-Validated custom solver output against spsolve_triangular to confirm correctness and numerical stability.

MTH371 Arnoldi Algorithm and Eigenvalues Project:

-Wrote a python function implementing the Arnoldi algorithm.

-Computed the eigenvalues of matrices.

-Compared the smallest and largest eigenvalues of the matrices.

-Tested the function with different matrices.

MTH371 Gauss-Seidel Method and L1-smoother Project:

-Wrote an iterative algorithm for solving Ax=b for a given sparse s.p.d. matrix A stored in csr format.

-Made: lower and upper matrices, a forward substitution function, a backward substitution function, a L1-smoother function, and a function that makes a regular Diagonal matrix.

-Made: the diagonal matrix representing the L1-smoother, the forward Gauss-Seidel iteration matrix, the backward Gauss-Seidel iteration matrix and the symmetric Gauss-Seidel iteration matrix.

MTH371 Sparse Matrices and LU Factorization Project:

-Created a matrix in COO format, Dense format, and in CSR format.

-Converted from COO format to CSR fomrat.

-Converted from CSR format to COO format.

-Wrote code for backward elimination with dense format matrix.

-Made a forward substitution function and a backward substitution function.

Personal Baseball Data Analysis Project:

-Renamed columns, used inequalities, mean, standard deviation, and variance.

-Applied max, min, and value_counts functions.
