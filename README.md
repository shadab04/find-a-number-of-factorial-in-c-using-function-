# find-a-number-of-factorial-in-c-using-function-
#include<stdio.h>
int fact(int n);
int main()
{
    printf("\n%d",fact(3));
    return 0;
}
int fact(int n)
{
    if(n==0)
    {
        return 1;
    }
    int factNm1=fact(n-1);
    int factN=factNm1*n;
    return factN;
}
