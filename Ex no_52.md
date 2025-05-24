## Task

# Write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

## Note

There is not built in max function in C. Code that will be reused is often put in a separate function, e.g. int max(x, y) that returns the greater of the two values.

## Input Format

Input will contain four integers - a,b,c,d , one on each line.

## Output Format

Print the greatest of the four integers.
Note: I/O will be automatically handled.

AIM:

To write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

Algorithm:

1.Define a function max_of_four() that takes four integers as arguments.

2.Use a series of comparisons to find the greatest among the four integers.

3.First, compare a and b to find the maximum of the two.

4.Then compare the result with c and d to get the maximum of all four.

5.Return the greatest value.

/*
C program to reverse a string.
Developed by: santhiya c
RegisterNumber:  212223060247
*/
#include <stdio.h>
int max_of_four(int a, int b, int c, int d)
{
    int max = a;

    if(b > max)
        max = b;
    if(c > max)
        max = c;
    if(d > max)
        max = d;

    return max;
}

int main()
{
    int a, b, c, d;

    // Read four integers
    scanf("%d", &a);
    scanf("%d", &b);
    scanf("%d", &c);
    scanf("%d", &d);

    // Output the greatest of the four integers
    printf("%d\n", max_of_four(a, b, c, d));

    return 0;
}

Output:

![image](https://github.com/user-attachments/assets/4dcf960d-6b82-450d-99fa-b6e64d3fdaa9)


Result:
Thus the program was executed and the output was verified successfully.



