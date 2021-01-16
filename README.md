# c
#include <stdio.h>
int main(void)
{
	int num;
	num = 1;

	printf("I am a simple ");
	printf("computer.\n");
	printf("My favorite number is %d because it is first.\n", num);/*notes*/

	getchar(); //让窗口运行完程序不自动关闭
	return 0;
}
2.2.1快速概要
1.stdio.h是c编译器软件包的标准部分，它提供键盘输入和屏幕输入的支持。
2.main（）是一个函数，表示总是被第一个调用的函数 int表明main（）函数返回一个整数，void表明main（）不带任何参数
现在只需记住int和void是标准ANSI C定义main（）的一部分
3.注释使用： /*xxxxxxxx*/
4.函数体开始的标志：左“{” 结束是右“}
5.int num是声明的意思 ，是说将使用一个名为num的变量，而且num是int(整数)类型.
6.printf()函数 在屏幕上显示（）的内容； 在程序中使用函数叫做调用函数
7.函数是C程序的基本模块
8.\n表示告诉计算机另起一行，即把光标移到下一行。
9.%d表示以何种形式输出变量的值，打印在何处，使用时一定要注意标出变量名称，例如第十行的末尾
10.这里的return 0 暂时看做结束main（）函数的要求
11.最后一定要以“}”结束整个函数体
