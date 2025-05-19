# EX 17 C Program to compare two strings without using strcmp().
## DATE:19/05/25
## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output
## Program:
```
/*
 C Program to compare two strings without using strcmp().
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int main() {
    char str1[100], str2[100];
    int i = 0, flag = 0;
    scanf("%s", str1);
    scanf("%s", str2);

    // Compare character by character
    while (str1[i] != '\0' || str2[i] != '\0') {
        if (str1[i] != str2[i]) {
            flag = 1;
            break;
        }
        i++;
    }

    // Output
    if (flag == 0)
        printf("Strings are equal.\n");
    else
        printf("Strings are not equal.\n");

    return 0;
}

## Output:

Strings are equal.

## Result:
Thus the program was executed and the output was verified successfully.
