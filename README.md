# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
i.L and U matrix

1. Start the program

2.Import the necessary libraries(numpy,scipy.linalg)

3.Define the matrix using numpy

4.Use lu(),lu_solve(),lu_factor() to get the solutions

5.End the program

ii.LU decomposition

1.Input Matrices:

2.Read the square coefficient matrix A (AMatrix).

3.Read the right-hand side vector or matrix B (BMatrix).

4.LU Factorization:

5.Perform LU factorization on A using lu_factor. This decomposes A into a lower triangular matrix (L) and an upper triangular matrix (U).

6.Solve the System:

7.Use lu_solve to solve the linear system 
𝐴
𝑋
=
𝐵

8.AX=B using the LU decomposition.

9.Output the Solution:

10.Print the solution matrix X which satisfies 
𝐴
𝑋
=
𝐵
AX=B.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:duraiarasan M
RegisterNumber:24901028

    import numpy as np
    from scipy.linalg import lu
    matrix=np.array(eval(input()))
    piv,l_matrix,u_matrix=lu(matrix)
    print(l_matrix)
    print(u_matrix) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:duraiarasan
RegisterNumber:24901028

    import numpy as np
    from scipy.linalg import lu_factor,lu_solve
    matrix=np.array(eval(input()))
    b=np.array(eval(input()))
    x=lu_factor(matrix)
    solution=lu_solve(x,b)
    print(solution)
    */
```

## Output:
![lu decomposition]()
![image1](<Screenshot 2024-12-04 212537.png>)
![image2](<Screenshot 2024-12-04 212554.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

