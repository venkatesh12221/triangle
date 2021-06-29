#include<stdio.h>
main()
{
floata,b,c,s,area;
printf("Enter the three sides\n");
scanf("%f%f%f",&a,&b,&c);
s=(a+b+c)/2;
area=sqrt(s*(s-a)*(s-b)*(s-c));
printf("area of triangle is %f\n",area);
}
