#include <stdio.h>

int main()
{
    int a,b;
    printf("enter the numbers:");
    scanf("%d%d",&a,&b);
     printf("a = %d and b =%d\n",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("a = %d and b =%d",a,b);

    return 0;
}# swapping-of-numbers
