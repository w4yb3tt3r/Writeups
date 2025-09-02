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
    <img title="" src="./images/1.png" alt="" data-align="center" width="287"><img title="" src="./images/2.png" alt="" width="486" data-align="center">
  
  **Linear Transformation:**

A transformation **L** is linear if it satisfies the following two properties:

1. L(a + b) = La + Lb

2. L(ca) = cL(a)
   
   N.B. **a,b** are vectors and **c** is a scalar.

<img title="" src="./images/3.png" alt="" data-align="center" width="400">
<img title="" src="./images/4.png" alt="" width="411" data-align="center">



3-dimension linear transformation

<img src="./images/5.png" title="" alt="" data-align="center">

<img src="./images/6.png" title="" alt="" data-align="center">

Basis and Dimension

<img src="./images/7.png" title="" alt="" data-align="center">

Determinant and linear dependence / independence

- If the deteminant of a matrix is 0, that means the rows or columns are linearly dependent.
  
  Also, suppose there are two vectors v1 and v2;
  
      v1 and v2 are said to be linearly dependent for a scalar c, iff v1 = c. v2

<img src="./images/8.png" title="" alt="" data-align="center"><img src="./images/9.png" title="" alt="" data-align="center">Also, **det(M1M2) = det(M1)*det(M2)**
