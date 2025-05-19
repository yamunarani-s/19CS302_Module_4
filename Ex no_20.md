# EX 20 C program to convert the given string to lowercase without using string functions.
## DATE:19/05/25
## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4.  Check for error
5. Run & Display the output
## Program:
```
/*
C program to convert the given string to lowercase without using string functions.
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int main() {
    char str[100];
    int i = 0;
    scanf("%s", str);  // Use fgets if you want to include spaces

    // Convert to lowercase
    while (str[i] != '\0') {
        if (str[i] >= 'A' && str[i] <= 'Z') {
            str[i] = str[i] + 32;  // Convert to lowercase
        }
        i++;
    }

    // Output
    printf("String in lowercase: %s\n", str);

    return 0;
}

/*
Developed by: YAMUNA RANI S
Register Number: 212223060309
*/

## Output:
String in lowercase: helloworld


## Result:
Thus the program was executed and the output was verified successfully.
