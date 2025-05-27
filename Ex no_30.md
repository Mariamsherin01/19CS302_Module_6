# EX 30 C program to Create a structure program to read(empno,dept & basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP) using nested structures;

## AIM:
To write a C program to Create a structure program to read(empno,dept & basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP) using nested structures;

## Algorithm
1. Define a nested structure with empno, dept, and salary details (basic_pay, da, hra, gross).
2. For each of the 3 employees, input empno, dept, and basic_pay.
3. Calculate da as 10% of basic_pay and hra as 30% of basic_pay.
4. Calculate gross salary = basic_pay + da + hra.
5. Print empno, dept, basic_pay, da, hra, and gross salary for each employee.

## Program:
```
/*
C program to Create a structure program to read(empno,dept & basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP) using nested structures;

Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include <stdio.h>
struct salary_detail
{
    int basic,da,hra;
};

struct employee
{
    int emp_no;
    char dept[20];
    struct salary_detail salary;
    float gross_salary;
}e[3];


int main()
{
   
for(int i=0; i<3; i++)
    {
        scanf("%d %s %d",&e[i].emp_no,e[i].dept,&e[i].salary.basic);
    }

for(int i=0; i<3; i++)
    {
        e[i].salary.da = (float) 10/100 * e[i].salary.basic;
        e[i].salary.hra = (float) 30/100 * e[i].salary.basic;
        e[i].gross_salary= e[i].salary.basic + e[i].salary.da + e[i].salary.hra;
    }
        
    printf("Details of the Employee: \n");
for(int i=0; i<3; i++)
    {
        printf("%d    %s           %d    %d    %d    %.2f\n",e[i].emp_no,e[i].dept,e[i].salary.basic,e[i].salary.da,e[i].salary.hra,e[i].gross_salary);
}
}
  
*/
```

## Output:

![image](https://github.com/user-attachments/assets/fc16fa6c-378f-4c7e-b891-4b6da67b7672)


## Result:
Thus the program was executed and the output was verified successfully.
