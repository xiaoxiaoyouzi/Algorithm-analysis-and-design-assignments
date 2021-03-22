#include<stdio.h>
#include<stdlib.h>

int BinarySearch(int T[], int n, int x)
{
	int low = 0;
	int high = n-1;
	int middle;
	while (low <= high)//设置跳出条件，当查找的最小边界大于最大边界时就跳出
	{
		middle = (low + high) / 2;   //找出中间值
		if (x < T[middle])high = middle - 1;     //向中间值的左半边查找
		else if (x > T[middle])low = middle + 1;     //向中间值的右半边查找
		else return middle;      //找到就返回下表
	}
	return 0;//没找到就输出0
}

int main() 
{
	int T[10] = {1,2,3,4,5,6,7,8,9,10};
	printf("%d\n", BinarySearch(T, 10, 8));
}
