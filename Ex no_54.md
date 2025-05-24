## print all the letters of the English alphabet.

SAMPLE OUTPUT : CAPS and add space to each alphabet

A B C D E F G H I J K L M N O P Q R S T U V W X Y Z

AIM:

To write a C program to print all the letters of the English alphabet.

Algorithm:

1.Use a loop to iterate over the ASCII values of uppercase English letters (from 'A' to 'Z').

2.Start from the ASCII value of 'A' (65) and loop until the ASCII value of 'Z' (90).

3.In each iteration, print the current letter followed by a space.

4.Print a newline after printing all the letters.

5.Ensure that each letter is separated by a space.

/*
C program to reverse a string.
Developed by: Santhiya c
RegisterNumber:  212223060247
*/
#include <stdio.h>

int main()

{
    for(char ch = 'A'; ch <= 'Z'; ch++)
    
    {
        printf("%c ", ch);
        
    }
    
    printf("\n");
    
    return 0;
}

output:

![image](https://github.com/user-attachments/assets/2fa64d0d-d44e-481a-bca5-0ab349065c9f)

Result:

Thus the program was executed and the output was verified successfully.
