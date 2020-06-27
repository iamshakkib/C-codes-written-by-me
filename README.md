*taking input from user to find loss or profit*

#include<stdio.h>
int main()
{
	int sp,cp,pro,loss;
	printf("enter the value of sp and cp ");
	scanf("%d %d",&sp,&cp);
	if(sp>cp)
	{
		pro=sp-cp;
	    printf("the seller has made a profit of %d",pro);
	}
	else
	{
		loss=cp-sp;
		printf("the seller has made a loss of %d",loss);
	}
}
*now its time for odd even problem*


#include<stdio.h>
int main()
{
	int m,d=2;
	printf("enter the value ");
	scanf("%d",&m);
	
	if(m%d==0)
	{
		printf("the number %d is even",m);
	}
	else
	{
		printf("the nuber is odd");
	}
}
*chal bhai doosra sawal functions pe chalte hain*

#include<stdio.h>
void add(int x, int y)
{
int result;
result = x+y;
printf("sum of %d and %d is %d.\n\n",x,y,result);
}
void main()
{
add(10,15);
}
