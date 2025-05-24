# EX 55 C program to find a square of number using function with arguments without return type.
## DATE:
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a program to square of the given number. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End 

## Program:
```
/*
C program to find a square of number using function with arguments without return type.
Developed by:santhiaya c  
RegisterNumber:212223060247  
*/
#include <stdio.h> 
int square(int num) { 
    return num * num; 
} 
int main() { 
    int number, result; 
    scanf("%d", &number); 
    result = square(number);  // Function call 
    printf("Square of %d is %d\n", number, result); 
} 
```

## Output:

![image](https://github.com/user-attachments/assets/e16da774-a0ed-4887-af2b-0d41c03ae0b8)



## Result:
Thus the program was executed and the output was verified successfully.
