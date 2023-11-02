# EX-02-2b-Nested-loop
## AIM:
Write a C program to print the given triangular  pattern using loop.
## ALGORITHM:
1. Declare a variable to store the number of rows in the triangle.
2. Use the printf function to prompt the user to enter the number of rows.
3. Use a loop (for or while) to iterate through each row.
4. Inside the loop, use another loop to print the desired number of asterisks for each row.
5. Continue the loop until you have printed the entire triangular pattern.
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int i,j,n;
    scanf("%d",&n);
    for(i=n;i>0;i--)
    {
        for(j=1;j<=i;j++)
        {
            printf("#");
        }
        printf("\n");
    }
    return 0;
    
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX-02-2b-Nested-loop/assets/118899387/6998417a-74b1-40ef-8d16-bc0355746e04)

## RESULT:
Thus the program  to print the given triangular  pattern using loop has been executed successfully
