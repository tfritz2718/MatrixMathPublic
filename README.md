# Matrix Math
This adds in the ability to create matrices and use them for mathematical operations using just one header file.

To create a matrix:
```
Matrix m = Matrix(#rows, #columns);
```
Mathematical operations are as simple as regular math:

**Addition (supports both constants and other matrices):
```
m = m + 5
m += 5
```
**Multiplication:
```
m *= 5
m = m * m2
```
