# EX 24 Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).
## DATE:
## AIM:
To Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).

## Algorithm
1. Start the program and define a structure with members: employee number, department, basic pay, and gross salary.

2. Declare an array of structures to store data for 3 employees.

3. Read employee number, department, and basic pay for each employee.

4. Calculate gross salary as the sum of basic pay, DA (10%), and HRA (30%).

5. Display all employee details along with the calculated gross salary and end the program.


## Program:
```
/*
A structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).
Developed by: Nabisha A
RegisterNumber:  212223060177
#include <stdio.h>

struct Employee {
    int empno;
    char dept[30];
    float basicPay;
    float grossSalary;
};

int main() {
    struct Employee emp[3];
    int i;

    for (i = 0; i < 3; i++) {
        printf("\nEnter details of Employee %d:\n", i + 1);
        printf("Employee Number: ");
        scanf("%d", &emp[i].empno);
        printf("Department: ");
        scanf(" %[^\n]", emp[i].dept);
        printf("Basic Pay: ");
        scanf("%f", &emp[i].basicPay);

        emp[i].grossSalary = emp[i].basicPay + (0.10 * emp[i].basicPay) + (0.30 * emp[i].basicPay);
    }

    printf("\n--- Employee Details with Gross Salary ---\n");
    for (i = 0; i < 3; i++) {
        printf("\nEmployee %d:\n", i + 1);
        printf("Emp No     : %d\n", emp[i].empno);
        printf("Department : %s\n", emp[i].dept);
        printf("Basic Pay  : %.2f\n", emp[i].basicPay);
        printf("Gross Salary: %.2f\n", emp[i].grossSalary);
    }

    return 0;
}

*/

```

## Output:
![image](https://github.com/user-attachments/assets/0d386f1e-eaee-4a2b-a049-34f06c50f9ca)




## Result:
Thus the program was executed and the output was verified successfully.
