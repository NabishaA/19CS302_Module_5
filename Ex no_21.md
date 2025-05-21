# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
1. Start the program and declare variables for base, height, and area.

2. Declare pointers for each of these variables.

3. Take input for base and height using pointers.

4. Perform the area calculation using the pointer values.

5. Display the area and end the program.   

## Program:
```
/*
C program to calculate the area of a triangle using pointer.
Developed by: 
RegisterNumber:
#include <stdio.h>

int main() {
    float base, height, area;
    float *pBase = &base, *pHeight = &height, *pArea = &area;

    printf("Enter base of the triangle: ");
    scanf("%f", pBase);

    printf("Enter height of the triangle: ");
    scanf("%f", pHeight);

    *pArea = 0.5 * (*pBase) * (*pHeight);

    printf("Area of the triangle = %.2f\n", *pArea);

    return 0;
}
 
*/
```

## Output:
![image](https://github.com/user-attachments/assets/5d9391f7-0423-4b81-8b1b-aeca232d89b8)



## Result:
Thus the program was executed and the output was verified successfully.
