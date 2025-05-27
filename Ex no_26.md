# EX 26 C program to find area of a circle & perimeter of a circle for the radius 35 using pointer 
## AIM:
To write a C program to find area of a circle & perimeter of a circle for the radius 35 using pointer 

## Algorithm
1. Declare variables for radius, area, and perimeter.
2. Assign the value 35 to the radius and create a pointer pointing to it.
3. Calculate the area using the formula: area = π * (*radius) * (*radius).
4. Calculate the perimeter using the formula: perimeter = 2 * π * (*radius).
5. Print the area and perimeter.
  

## Program:
```
/*
C program to find area of a circle & perimeter of a circle for the radius 35 using pointer 
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    int *N;
    N=&n;
    float area=3.14**N**N;
    float peri=2*3.14**N;
    printf("Area of Circle = %.2f\n",area);
    printf("Perimeter of Circle = %.2f",peri);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/7c2f1e9a-a7e3-4ca2-ae2f-b0f98342a288)


## Result:
Thus the program was executed and the output was verified successfully.
