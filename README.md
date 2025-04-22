# -solution-of-finding-absolute-diagonal-difference-in-square-matrix

1.Input the size of the matrix n (i.e., the matrix will be n x n).
2.Create an empty matrix list.
3.Repeat n times to input the matrix:
For each iteration:
Input a row of n integers.
Convert the input into a list of integers.
Append this list (row) to the matrix.

4.Initialize two variables to store diagonal sums:
primary_sum = 0, secondary_sum = 0

5.Loop through the matrix using index i from 0 to n-1:
Add the value at the primary diagonal position matrix[i][i] to primary_sum.
Add the value at the secondary diagonal position matrix[i][n-1-i] to secondary_sum.

6.Calculate the absolute difference between primary_sum and secondary_sum.

7.Output the result:
"absolute diagonal difference: <difference>"

