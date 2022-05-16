# kasim
#include<stdio.h>
void main ()
{
	int n,count=0;
	printf("enter the n valuve to count the digits\n");
	scanf("%d",&n);

	while(n!=0)
	{
		count++;
		n=n/10;
	}
	 printf("number of conts =%d",count);
}
