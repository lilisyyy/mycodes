# mycodes
test
\\yesorno
#include<stdio.h>
int main()
{
	int a;
	printf("请输入一个数:\n");
	scanf("%d",&a);
	if(a % 5 == 0 && a % 7!= 0){
		printf("Yes");
	}else{
		printf("No");
	}
	return 0;
}
