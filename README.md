# exp8

Indraniel Wandkar 
25070123156

Experiment: Python Looping and Matrix Operations
Aim

To study and implement looping constructs in Python and apply them to solve problems such as number generation, summation, matrix operations, permutations, and pattern printing.

Program 1: Print Numbers from 1 to 6
Theory

The for loop in Python is used to iterate over a sequence. The range() function generates a sequence of numbers.
range(1,7) generates numbers from 1 to 6.

Algorithm

Start

Use for x in range(1,7)

Print the value of x

Stop

Program 2: Print Even Numbers from 2 to 10
Theory

The range(start, stop, step) function allows control over increments.
Using range(2,11,2) generates even numbers from 2 to 10.

Algorithm

Start

Use for i in range(2,11,2)

Print i

Stop

Program 3: Sum of First n Natural Numbers
Theory

The sum of first n natural numbers can be calculated using iteration by adding numbers from 1 to n inside a loop.

Algorithm

Start

Input value of n

Initialize sum = 0

For i from 1 to n

Add i to sum

Display the sum

Stop

Program 4: Display Elements of a 3×3 Matrix
Theory

A matrix in Python can be represented using a list of lists. Nested loops are used to access rows and columns.

Algorithm

Start

Define matrix A

Use outer loop for rows

Use inner loop for columns

Print each element A[i][j]

Stop

Program 5: Multiplication of Two 3×3 Matrices
Theory

Matrix multiplication is performed by multiplying corresponding row elements of the first matrix with column elements of the second matrix and summing them.
Triple nested loops are required:

First loop for rows

Second loop for columns

Third loop for multiplication and addition

Algorithm

Start

Define matrices A and B

Initialize result matrix with zeros

For each row i

For each column j

For each element k

Compute Result[i][j] += A[i][k] * B[k][j]

Display the result matrix

Stop

Program 6: Generate Permutations of Three Numbers
Theory

Permutations are different arrangements of elements. Nested loops with conditional checking ensure all values are distinct before printing.

Algorithm

Start

Store three numbers in a list

Use three nested loops

Check that all selected elements are different

Print valid combinations

Stop

Program 7: Pattern Printing
Theory

Pattern printing is done using loops and string multiplication. Spaces and stars are printed based on loop control.

Algorithm (Inverted Pattern)

Start

Loop from 5 down to 1

Print "* " multiplied by loop value

Stop

Algorithm (Pyramid Pattern)

Start

Set number of rows

For each row

Print spaces (rows - i)

Print "* " repeated i times

Stop

Conclusion

This experiment helped in understanding the practical implementation of loops in Python. Different applications of loops such as number generation, summation, matrix traversal, matrix multiplication, permutation generation, and pattern printing were successfully implemented. The experiment strengthened the understanding of nested loops and their importance in solving computational problems.
