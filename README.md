include <stdio.h>
int main()
{
   int a, b,c;
   scanf("%d%d",&a,&b);
   if(a>b)
     {c=b;b=a;a=c;}
    printf("%d",a);
    return 0;
  }
