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
