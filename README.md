# nested-for-loops
to print binary numbers in right triangle pattern

#include<stdio.h>
int main()
{
int count=1;
int i,j;
for(i=1;i<=6;i++)
{
printf("\n");
for(j=1;j<=i;j++)
{
printf("%d",count%2);
count++;
}
if(i%2==0)
count=i;
else
count=0;
}
return 0;
}
