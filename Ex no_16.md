# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
   
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output
## Program:
```
/*
C program to find minimum between three fraction numbers using conditional operator.
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int main() {
    float a, b, c, min;
    scanf("%f %f %f", &a, &b, &c);

    // Using conditional operator to find minimum
    min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

    // Output
    printf("Minimum among the three numbers is: %.2f\n", min);

    return 0;
}

## Output:
3.2 5.1 1.8
Minimum among the three numbers is: 1.80


## Result:
Thus the program was executed and the output was verified successfully.
