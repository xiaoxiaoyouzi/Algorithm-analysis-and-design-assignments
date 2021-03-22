#include<stdio.h>
#include<stdlib.h>

int SequentialSearch(int T[], int n, int x)//传递过来数组的第一个值的地址
{
	int i;
	for (i = 0; i < n; i++)//从0开始遍历一遍数组
	{
		if (T[i] == x)return i;//找到就输出下标
	}
	return 0;//没找到就输出0
}

int main() 
{
	int T[10] = {1,2,3,4,5,6,7,8,9,10};
	printf("%d\n", SequentialSearch(T, 10, 8));
}
