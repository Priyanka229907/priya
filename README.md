#include <stdio.h>

int main()
{
   int X,P,a,b,c;
   scanf("%d %d",&X,&P);
   a=X*(P/100);
   b=a*(P/100);
   c=b*(P/100);
   printf("%d\n",c);
}
