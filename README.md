# C-program-for-swapping-2-numbers
C program to perform the swapping of 2 numbers
 without using third variable
#include<stdio.h>
int main()
{
int x,y;
printf("enter the value of x and y :\n");
scanf("%d%d",&x,&y);
printf("before swapping:%d%d",x,y);
x=x+y;
y=x-y;
x=x-y;
printf("\n after swapping : %d %d ",x,y);
return 0;
}
