#define _CRT_SECURE_NO_WARNINGS

#include<stdio.h>

int main(void){

	int N = 0;
	int sum = 0;
	char num[100] = { 0, };

	scanf("%d", &N);
	scanf("%s", &num);

	for (int i = 0; i < N; i++)
		sum += num[i] - '0';
	printf("%d", sum);

	return 0;
	}
