# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

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

