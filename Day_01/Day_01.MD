## Day 01 - Complex Numbers and Linear Algebra Basics

### Cheatsheet / Topics Covered

- Vector
  
  - Vector addition
  
  - Scalar Multiplication

- Linear Combination
  
  - eg: i and j --> (3)i + (-4)j

- Basis (i,j)

- Span (Set of vectors you can reach from the linear combination of two vectors)

- Matrices
  
  - Matrix addition
  
  - Matrix multiplication  
    
    <p align="center"><img src="./images/1.png" width="287"></p>
    <p align="center"><img src="./images/2.png" width="486"></p>
  
  **Linear Transformation:**

A transformation **L** is linear if it satisfies the following two properties:

1. L(a + b) = La + Lb

2. L(ca) = cL(a)
   
   N.B. **a,b** are vectors and **c** is a scalar.

<p align="center"><img src="./images/3.png" width="400"></p>
<p align="center"><img src="./images/4.png" width="411"></p>

### 3-dimension linear transformation

<p align="center"><img src="./images/5.png"></p>
<p align="center"><img src="./images/6.png"></p>

### Basis and Dimension

<p align="center"><img src="./images/7.png"></p>

### Determinant and linear dependence / independence

- If the determinant of a matrix is 0, that means the rows or columns are linearly dependent.
  
  Also, suppose there are two vectors v1 and v2;
  
      v1 and v2 are said to be linearly dependent for a scalar c, iff v1 = c. v2

<p align="center"><img src="./images/8.png"></p>
<p align="center"><img src="./images/9.png"></p>  
Also, **det(M1M2) = det(M1)*det(M2)**
