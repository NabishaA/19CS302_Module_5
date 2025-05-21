# EX 23 C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
## DATE:
## AIM:
To write a C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## Algorithm
1. Start the program and define a structure with members for name, ID, age, and salary.

2. Declare an array of structures to hold data for multiple employees.

3. Read the number of employees and their details using a loop.

4. Display the stored employee details using another loop.

5.End the program.
  

## Program:
```
/*
C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
Developed by: Nabisha A 
RegisterNumber:  212223060177
#include <stdio.h>

struct Employee {
    char name[50];
    int id;
    int age;
    float salary;
};

int main() {
    int i, n;

    printf("Enter the number of employees: ");
    scanf("%d", &n);

    struct Employee emp[n];

    for (i = 0; i < n; i++) {
        printf("\nEnter details of employee %d:\n", i + 1);
        printf("Name: ");
        scanf(" %[^\n]", emp[i].name);
        printf("ID: ");
        scanf("%d", &emp[i].id);
        printf("Age: ");
        scanf("%d", &emp[i].age);
        printf("Salary: ");
        scanf("%f", &emp[i].salary);
    }

    printf("\n--- Employee Details ---\n");
    for (i = 0; i < n; i++) {
        printf("\nEmployee %d:\n", i + 1);
        printf("Name: %s\n", emp[i].name);
        printf("ID: %d\n", emp[i].id);
        printf("Age: %d\n", emp[i].age);
        printf("Salary: %.2f\n", emp[i].salary);
    }

    return 0;
}

*/
```

## Output:
![image](https://github.com/user-attachments/assets/3bd32337-9520-4777-b973-e8b7c4df9ba4)




## Result:
Thus the program was executed and the output was verified successfully.
