/* Automatic result calculator */ 
#include <stdio.h>
int main(){
	
	float a,b,c,d,e;
	char str[100];
	printf("Enter your Full Name: \n");
	scanf("%[^\n]s", &str);
	printf("Enter your mark in English: \n");
	scanf("%f", &a);
	printf("Enter your mark in Nepali: \n");
	scanf("%f", &b);
	printf("Enter your mark in Accountancy: \n");
	scanf("%f", &c);
	printf("Enter your mark in Economics: \n");
	scanf("%f", &d);
	printf("Enter your mark in Compter Science: \n");
	scanf("%f", &e);
	printf("__________________________________________________\n");
	printf("__________________________________________________\n");
	printf("                   RESULT");
	printf("\nName: %s\n", str);

	printf("English: %f \n", a);
	printf("Nepali: %f \n", b);
	printf("Accountancy: %f\n", c);
	printf("Economics: %f\n", d);
	printf("computer Science: %f\n", e);
	float sum= a+b+c+d+e;
	float divide= sum/5;
		printf("__________________________________________________\n");
	
	printf("Grand Total: %f\n", sum);
	printf("Percentage: %f %\n", divide);
	
		if (divide<=10){
		printf("Grade: E");
	}
	else if(divide<=20){
		printf("Grade: E+");
	}
	else if(divide<=30){
		printf("Grade: D");
	}
	else if(divide<=40){
		printf("Grade: D+");
	}
	else if(divide<=50){
		printf("Grade: C");
	}
	else if(divide<=60){
		printf("Grade: C+");
	}
	else if(divide<=70){
		printf("Grade: B");
	}
	else if(divide<=80){
		printf("Grade: B+");
	}
	else if(divide<=90){
		printf("Grade: A");
	}
	else if(divide<=100){
		printf("Grade: A+");
	}
	
	if(sum<200){
		printf("\nStatus: Failed\n");
	}
	else{
		printf("\nStatus: Passed\n");
	}
		printf("__________________________________________________\n");
		printf("__________________________________________________\n");
	
}
