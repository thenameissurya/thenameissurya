#include <stdio.h>
int fibo(int n)
{
  if (n<=2)return 1 ;
  return fibo(n-1) + fibo(n-2);
}
int main ()
{
    int a ;
    printf("The value of fibo num : ");
    scanf("%d",&a);
   int b = fibo(a);
   printf("The fibo number : %d ",b);
}
