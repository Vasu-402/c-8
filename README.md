#include <stdio.h>

int main() {
   int n, sum1=0, sum2=0, i;
   printf("enter the number:");
   scanf("%d",&n);
   for (int i=1;i<=n;i++)
   {
      if(i%2==1)//i%2!=0 is also correct//i%2==1 for even
      {
          printf("%d\n",i);
          sum1+=i;
      }
      
   }
   printf("sum of odd numbers %d ",sum1);
   
  return 0;
}
