# EX 25 C program to check whether a given character is a vowel or consonant using pointer
## DATE:
## AIM:
To write a C program to check whether a given character is a vowel or consonant using pointer

## Algorithm
1. Start the program and declare a character variable and a pointer to it.

2. Read a character from the user and store its address in the pointer.

3. Convert the character to lowercase (optional for uniformity).

4. Check whether the character pointed to is a vowel (a, e, i, o, u).

5. Display whether it is a vowel or consonant and end the program.

 

## Program:
```
/*
C program to check whether a given character is a vowel or consonant using pointer
Developed by: Nabisha A
RegisterNumber:  212223060177
#include <stdio.h>
#include <ctype.h>

int main() {
    char ch;
    char *ptr = &ch;

    printf("Enter an alphabet: ");
    scanf(" %c", ptr);

    *ptr = tolower(*ptr);  // Convert to lowercase for uniform comparison

    if ((*ptr >= 'a' && *ptr <= 'z')) {
        if (*ptr == 'a' || *ptr == 'e' || *ptr == 'i' || *ptr == 'o' || *ptr == 'u') {
            printf("The character '%c' is a vowel.\n", *ptr);
        } else {
            printf("The character '%c' is a consonant.\n", *ptr);
        }
    } else {
        printf("Invalid input. Please enter an alphabet.\n");
    }

    return 0;
}

*/
```

## Output:
![image](https://github.com/user-attachments/assets/a97bf9d4-7667-431f-be58-e909ec13938c)



## Result:
Thus the program was executed and the output was verified successfully.
