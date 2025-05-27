# EX 27 C program to check given input is even or odd using calloc().
## AIM:
To write a C program to check given input is even or odd using calloc().

## Algorithm
1. Use calloc() to dynamically allocate memory for an integer.
2. Read an integer from the user and store it in the allocated memory.
3. Use an if-else statement to check if the number is divisible by 2.
4. Print "Even" if divisible, else print "Odd", then free the memory.
  

## Program:
```
/*
C program that to check given input is even or odd using calloc().
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include<stdio.h>
#include<stdlib.h>
int main()
{
    int *p=(int*)calloc(1,sizeof(int));
    scanf("%d",p);
    if(*p%2==0)
    {
    printf("%d is Even Number",*p);
    }
    
    else
    printf("%d is Odd Number",*p);
    
    free(p);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/282ad4fe-98c0-4cc3-9a07-207229558005)


## Result:
Thus the program was executed and the output was verified successfully.
