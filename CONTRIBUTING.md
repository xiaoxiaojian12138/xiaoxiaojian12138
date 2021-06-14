#define  _CRT_SECURE_NO_WARNINGS 
#include<stdio.h>
#include<string.h>
int main()
{
	int age = 50;
	if (age < 18)
	{
		printf("未成年\n");
		printf("不能谈恋爱\n");
	}
	else
	{
		if (age >= 18 && age < 30)
			printf("青年\n");
		 if (age >= 30 && age < 50)
			printf("壮年\n");
		 if (age >= 50 && age < 90)
			printf("老年\n");
		else
			printf("老不死\n");
	}
	return 0;
