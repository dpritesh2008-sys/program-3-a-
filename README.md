# program-3-a-
C module 3

EX NO-3)a)- Decimal to Binary.

Date:25/3/2026
Name: Ritesh DP
Ref no: 25015366

AIM: To write a C program to convert a decimal number to binary number.

ALGORITHM:

1) Get a decimal number as input from the user.
2) Divide the number again and again by 2 and store the remainder in an array.
3) Print the elements of the array in reverse using for loop.


PROGRAM:
```
#include <stdio.h>
int tobinary(int );
int tobinary(int num)
{
    int bin[32],ind=0;
    while(num>0)
    {
        bin[ind]=num%2;
        num/=2;
        ind++;
    }
    for(int j=ind-1;j>=0;j--)
    {
        printf("%d",bin[j]);
    }
    return 0;
}
int main()
{
    int num;
    scanf("%d",&num);
    printf("%d in decimal = ",num);
    tobinary(num);
    printf(" in binary");
    
}
```
OUTPUT:

<img width="811" height="197" alt="Screenshot 2025-10-20 101351" src="https://github.com/user-attachments/assets/2182c8cf-3dbb-4466-bce7-20dc1e74d26d" />


RESULT:
Thus the C program to convert the given decimal number to binary number is executed successfully. 












   
