# Beginner-C-Language
dynamic
 # first day
 hello world


int main()
{
    int a=10;
	int* p=&a;
	*p=20;
	printf("%p",&a);
	printf("%p\n",p);
	printf("%d",a);
	
	struct Book b1 = {"C语言程序设计",55};
	struct Book* p=&b1;
	printf("%p\n",p);
	printf("书名：%s\n",b1.name);
	printf("价格：%d\n",(*p).price);
	b1.price=15;
	printf("修改后的价格：%d\n",p->price);
	return 0;  
}
/*#include"stdio.h"
int main()
{
	int age=18;
	if(age<18)
	printf("我没有成年\n");
	else
	printf("我成年啦\n");
	return 0;
}*/
#include<stdio.h>
int main()
{
	//int num =2;
	int input=0;
	scanf("%d",&input);
	if(input%2!=0)
	printf("number为奇数");
	else
	printf("number不为奇数");
	return 0;
}
