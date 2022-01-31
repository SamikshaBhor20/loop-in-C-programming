//# loop-in-C-programming
//Drawing a given pattern in C using nested loop

#include<stdio.h>
int main()
{
  int i,j,n;
  printf("Enter a value of: ");
  scanf("%d",&n);
  for(i=0;i<=n;i++)
  {
    for{j=1;j<=i;j++);
    {
      if((i+j)%2==0)
      {
        printf("0");
      }
      else
      {
        printf("1");
      }
    }
  }
  return 0;
 }
     
	

	

