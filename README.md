//Celsius-to-Fahrenheit.c
//code for converting the Celsius  into Fahrenheit 
#include<stdio.h>
int main()
{
	float C,F;
	printf("enter the temperature in celsius: ");
	scanf("%f",&C);
	F=(C*9/5)+32;
	printf("temperature in farenheit= %.2f",F);
	return 0;
	
}
