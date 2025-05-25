# Distance-travelled
#include<stdio.h>
void main()
{
float u,a,t,d;
printf("Enter the acceleration value : ");
scanf("%f",&a);
printf("Enter the initial velocity : ");
scanf("%f",&u);
printf("Enter the time taken : ");
scanf("%f",&t);
d = u*t +(0.5) * a*t*t;
printf("Distance travelled : %f\n",d);
}
