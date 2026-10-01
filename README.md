#include <stdio.h>

int main()
{
  int a,b;
  printf("Enter the two numbers: ");
  scanf("%d%d",&a,&b);
    if(a>b){
      printf("the greatest no.is:%d",a);
    }
    if(b>a){
        printf("the greatest no. is:%d",b);
    }

    return 0;
}