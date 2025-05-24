# EX 51 C program to reverse a string.
## DATE:
## AIM:
To write a C program to reverse a string.

## Algorithm
1.Define a function reverse() that takes a string as an argument.

2.Find the length of the string.

3.Swap characters from both ends using a loop until the middle of the string is reached.

4.Use a temporary variable to hold characters during swapping.

5.Print the reversed string. 

## Program:
```
/*
C program to reverse a string.
Developed by:santhiya c 
RegisterNumber:212223060247  
*/
#include <stdio.h>
#include <string.h>

void reverse(char str[])
{
    int start = 0;
    int end = strlen(str) - 1;
    char temp;

    while(start < end)
    {
        temp = str[start];
        str[start] = str[end];
        str[end] = temp;
        start++;
        end--;
    }
}

int main()
{
    char str[100];

    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);

    // Remove newline character if it's read by fgets
    str[strcspn(str, "\n")] = '\0';

    reverse(str);

    printf("Reversed string: %s\n", str);

    return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/c4abe990-63df-40d9-a1d5-68a47d2dd68f)




## Result:
Thus the program was executed and the output was verified successfully.
