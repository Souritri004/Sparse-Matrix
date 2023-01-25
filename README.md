# Sparse-Matrix
Problem statement.
 Write a program to read a square matrix of order 4. Also, perform a test to check if the entered matrix is a sparse matrix. If the matrix is a sparse matrix, then write a function to represent the given sparse matrix in a multi dimensional array.
  Problem Description. 
A matrix is said to be sparse matrix if more than 50% of the elements of that are 0. It implies that it contains very less non-zero elements. A sparse matrix takes unnecessary space in the memory as most of the elements are zero. if we can devise a method to store only non zero elements of the array then considerable space could be saved. Hence, there are certain methods of representing such sparse matrix. The problem states one such methods to demonstrate where the non-zero elements of the matrix is represented by a multi dimensional array.
  Aim.
 The aim of the assignment is to demonstrate the use of multi dimensional array to represent a sparse matrix. It is necessary to write a modular program with a scope of reusability and easier debug. The variable names should be defined in such a way that it conveys a significant meaning to the debugger.
  Objectives.
 The following objectives is set for solving the stated problem. 
          (a) A driver program to control all modules of the problem.---->Prototype int main(){};
          (b) Reading, printing to be done through subprograms. ----->Prototype int **scanMatrix(), int **printMatrix();
          (c) Matrix to be checked whether it is a sparse matrix or not--->Prototype Boolean checkMatrix(int **ptrMatrix);
          (d) If the given matrix is a sparse then represent in M-D  ----->Proto int **sparseRepresentation(int **ptrMAtrix);
  Algorithm. 
(Test a matrix to be sparse)
            1.	Declare and initialize a two-dimensional array intArray[][].
            2.	Loop through the array and count the number of zeroes present in the given array and store in the variable count.
            3.	Calculate the size of the array by multiplying the number of rows with many columns of the array.
            4.	If the count is greater than size/2, given matrix is the sparse matrix. That means, 
                most of the elements of the array are zeroes.
            5.	Else, the matrix is not a sparse matrix.
