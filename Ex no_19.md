# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## DATE: 19/05/25
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output  

## Program:
```
/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int main() {
    int num, leftShift, rightShift;

    // Input
    printf("Enter an integer: ");
    scanf("%d", &num);

    // Perform shift operations
    leftShift = num << 1;   // Left shift by 1 bit
    rightShift = num >> 1;  // Right shift by 1 bit

    // Output
    printf("Original number: %d\n", num);
    printf("After left shift (num << 1): %d\n", leftShift);
    printf("After right shift (num >> 1): %d\n", rightShift);

    return 0;
}
/*
Developed by: YAMUNA RANI S
Register Number:212223060309
*/


## Output:
Enter an integer: 10
Original number: 10
After left shift (num << 1): 20
After right shift (num >> 1): 5



## Result:
Thus the program was executed and the output was verified successfully.
