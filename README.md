# test-9-16
#include <stdio.h>

int main()
{
	int num1 = 0;
	int num2 = 0;
	int sum = 0;
	scanf("%d%d",&num1,&num2);
	int sum = num1 + num2;
	printf("sum = %d\n",sum);
	return 0;
}
int main(){
	int i = 0;
	while(i<=100){
		if(i % 2 == 1)//if(i % 2 != 0)
			printf("%d ",i);
		i++;//i+=2;
	}
	return 0;
}
int main()
{
	int day = 0;
	scanf("%d\n",&day);
	switch(day)
	{
	case 1:
		printf("星期一\n");
		break;
	case 2:
		printf("星期2\n");
		break;
	case 3:
		printf("星期3\n");
	case 4:
	case 5:
	case 6:
	case 7:
		printf("星期7\n");
	default:
		break;
	}
	return 0;
}
int main(){
	int i = 1;
	while(i<=10){
		printf("%d ",i);
		i++;
	}
	return 0;
}
int main()
{
	int i =0;
	while(i<=10){
		i++;
		if(i == 5)
			continue;
			//break;
		printf("%d ",i);
		//i++;
	}
	return 0;
}
