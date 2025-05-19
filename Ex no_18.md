# EX 18 C program to find frequency of a character in the given input.
## DATE:19/05/25
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output

## Program:
```
/*
C program to find frequency of a character in the given input.
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int main() {
    char str[100], ch;
    int i, count = 0;
    scanf("%s", str);  // use scanf for single-word input; use fgets for full line if needed
    scanf(" %c", &ch);  // space before %c to consume any leftover newline

    // Counting frequency
    for (i = 0; str[i] != '\0'; i++) {
        if (str[i] == ch) {
            count++;
        }
    }

    // Output
    printf("Frequency of '%c' = %d\n", ch, count);

    return 0;
}


## Output:

Frequency of 'l' = 2

## Result:
Thus the program was executed and the output was verified successfully.
