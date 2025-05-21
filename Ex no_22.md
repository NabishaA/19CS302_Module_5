# EX 22 C program to count total number of even elements in an array using calloc().
## DATE:
## AIM:
To write a C program to count total number of even elements in an array using calloc().

## Algorithm:
 1. Start the program and declare variables for size, counter, and a pointer to hold array elements.

 2. Read the size of the array from the user.

 3. Allocate memory for the array using calloc().

 4. Read array elements from the user and count how many are even.

 5. Display the count of even elements and end the program. 

## Program:
```
/*
C program to count total number of even elements in an array using calloc().
Developed by: Nabisha A
RegisterNumber:  212223060177
*/ #include <stdio.h>
#include <stdlib.h>

int main() {
    int *arr, size, i, count = 0;

    printf("Enter the number of elements: ");
    scanf("%d", &size);

    arr = (int *)calloc(size, sizeof(int));

    if (arr == NULL) {
        printf("Memory allocation failed.\n");
        return 1;
    }

    printf("Enter %d elements:\n", size);
    for (i = 0; i < size; i++) {
        scanf("%d", &arr[i]);
    }

    for (i = 0; i < size; i++) {
        if (arr[i] % 2 == 0

```

## Output:
![image](https://github.com/user-attachments/assets/3b50b2ad-ef25-4ba9-8725-aad4425a4fd6)



## Result:
Thus the program was executed and the output was verified successfully.
