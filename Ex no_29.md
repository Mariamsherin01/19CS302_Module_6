# EX 29 C program to Create a structure to read customer no,prev reading & current reading as input for eb calculation bill for 3 Customers
## AIM:
To write a C program to Create a structure to read customer no,prev reading & current reading as input for eb calculation bill for 3 Customers

## Algorithm
1. Define a structure with fields: customer number, previous reading, and current reading.
2. Declare an array of the structure for 3 customers.
3. Use a loop to read customer details (number, previous, and current readings).
4. Calculate units consumed as (current reading - previous reading) for each customer.
5. Display the customer number and units consumed for each customer.
  

## Program:
```
/*
C program to Create a structure to read customer no,prev reading & current reading as input for eb calculation bill for 3 Customers
Developed by: Mariam Sherin
RegisterNumber:   212222060143
#include <stdio.h>

struct Customer {
    int cust_no;
    int prev_reading;
    int curr_reading;
};

int main() {
    struct Customer c[3];
    int i, units;

    // Reading input
    for(i = 0; i < 3; i++) {
        printf("Enter details for Customer %d:\n", i+1);
        printf("Customer Number: ");
        scanf("%d", &c[i].cust_no);
        printf("Previous Reading: ");
        scanf("%d", &c[i].prev_reading);
        printf("Current Reading: ");
        scanf("%d", &c[i].curr_reading);
    }

    // Displaying output
    printf("\nElectricity Bill Details:\n");
    for(i = 0; i < 3; i++) {
        units = c[i].curr_reading - c[i].prev_reading;
        printf("Customer No: %d | Units Consumed: %d\n", c[i].cust_no, units);
    }

    return 0;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/61dff3bc-c9f3-4e5c-a225-55978aac9c03)


## Result:
Thus the program was executed and the output was verified successfully.
