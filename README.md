EX-21-POINTERS
# AIM:
Write a C program to convert a 23.65 into 25 using pointer

## ALGORITHM:
1.	Declare a double variable to hold the floating-point number (23.65).
2.	Declare a pointer to double to point to the address of the variable.
3.	Use the pointer to modify the value to 25.0.
4.	Print the modified value.

## PROGRAM:

![image](https://github.com/user-attachments/assets/d6915439-a290-4a27-8c64-e3433e372df5)

## OUTPUT:
 	

![image](https://github.com/user-attachments/assets/50303ff2-d21f-45f0-8285-e15d6fb7365e)










## RESULT:
Thus the program to convert a 23.65 into 25 using pointer has been executed successfully.
 
 


# EX-22-FUNCTIONS AND STORAGE CLASS

## AIM:

Write a C program to calculate the Product of first 12 natural numbers using Recursion

## ALGORITHM:

1.	Define a recursive function calculateProduct that takes an integer parameter n.
2.	Return n multiplied by the result of the calculateProduct function called with n - 1.
3.	Declare an integer variable n and an unsigned long long variable product.
4.	Initialize n with the value 12 (for the first 12 natural numbers).
5.	Call the calculateProduct function with n and store the result in the product variable.
6.	Print the result, indicating it is the product of the first 12 natural numbers.

## PROGRAM:



![image](https://github.com/user-attachments/assets/4a39d0d7-1e51-46c3-86e8-6077f5f4a577)

## OUTPUT:

![image](https://github.com/user-attachments/assets/9a47a0e9-1be3-47fa-b772-5a3c1ca4fef7)

## RESULT:

Thus the program has been executed successfully.
 
 


# EX-23-ARRAYS AND ITS OPERATIONS

## AIM:

Write C Program to find Sum of each row of a Matrix

## ALGORITHM:

1.	Declare and initialize the matrix with the desired values.
2.	Create a loop to iterate through each row of the matrix.
3.	Inside the loop, calculate the sum of the elements in each row.
4.	Print the sum for each row.

## PROGRAM:


![image](https://github.com/user-attachments/assets/a76c9049-e772-4295-93fa-a302a675feb3)


## OUTPUT



![image](https://github.com/user-attachments/assets/0108dd9c-67b6-4517-9d61-0ef4cbda32c6)

 
 

 ## RESULT
 


# EX-24-STRINGS

## AIM:

Write C program for the below pyramid string pattern. Enter a string: PROGRAM Enter number of rows: 5 P R O G R A M P R O G R A M P R O G R A M

## ALGORITHM:

1.	Input the number of rows for the pyramid (e.g., num_rows).
2.	Initialize variables:i for the row count (starting from 1),j for the character count (starting from 1)
3.	Start a loop for i from 1 to num_rows (for each row of the pyramid).
4.	Calculate the midpoint position as midpoint = (2 * num_rows - 1) / 2.
5.	End the program.

## PROGRAM:


![image](https://github.com/user-attachments/assets/0db79226-5b03-4209-99a8-0425ee121a25)

 ## OUTPUT


 ![image](https://github.com/user-attachments/assets/c270588f-db89-4003-8e70-f3ecc8f3b568)


## RESULT

Thus the C program to String process executed successfully


# EX -25 –DISPLAYING ARRAYS USING POINTERS
## AIM

Write a c program to read and display an array of any 6 integer elements using pointer

## ALGORITHM
Step 1: Start the program.
Step 2: Declare the following:
•	Integer variable i for iteration.
•	Integer variable n to store the number of elements.
•	Integer array arr[10] to hold up to 10 elements.
•	Integer pointer parr and initialize it to point to the array arr.
Step 3: Read the value of n (number of elements) from the user.
Step 4: Loop from i = 0 to i < n:
•	Read an integer value and store it in the address parr + i using pointer arithmetic.
Step 5: Loop from i = 0 to i < n:
•	Print the element at *(parr + i) using pointer dereferencing.
Step 6: End the program.

## PROGRAM


![image](https://github.com/user-attachments/assets/77206dae-2532-44cb-a1a6-e0d36819206f)

## OUTPUT


![image](https://github.com/user-attachments/assets/44af33ea-0fd9-4da5-a9a9-4872e1ca7718)

 

## RESULT

Thus the C program to read and display an array of any 6 integer elements using pointer has been executed


