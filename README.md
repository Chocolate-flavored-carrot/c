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
2.2.2细节分析
1.#include指令和头文件
#include<stdio.h> 相当于是把stdio.h文件中的内容输入到了改行所在的位置。
#include这条指令是一条c预处理器指令，通常c编译器在编译前会对源代码做准备工作 即预处理。（#表示C预处理器在编译器接手之前处理这条指令）
所有的c编译器软件包都提供stdio.h文件，它包含了供编译器使用的各种函数，少了它编译器无法识别编译函数程序会无法运行。
stdio.h文件名含义是  标准输入/输出头文件
c程序顶部的信息集合被称为头文件（.h的文件）
头文件包含了编译器创建最终可执行程序要用到的信息。它的存在帮助编译器把你的程序正确的组合到一起。
我们很好奇为啥，不直接把输入和输出这些基本功能内置在语言里呢？？？ 原因之一就是并不是所有的程序都会用到输入/输出（I/O）包，因此这样可以大大减少运行程序时所用的内存因此大大提高了效率
所以C语言成为流行的嵌入式编程语言。
2.main（）函数
C程序一定从main（）函数开始执行，除了main（）函数你可以任意命名其他函数，而且main函数必须是开始的函数。
通常函数后面的圆括号包含一些传入函数的信息。上例中没有传入任何信息因此填的是void（void 被翻译为"无类型"）
3.注释
/*xxx*/    用//只能写一行。
4.花括号、函数体和块
花括号除了能标记函数体的开始和结束，还可以用于把函数中的多条语句合并为一个单元或块。
5.声明
int num 就是说函数中有num这个变量，而且int 说明num是整数
int是C语言的一个关键字，表示一种基本的C语言数据类型。
num是一个标识符，也就是一个变量、函数或者其他实体的名称
因此，声明把特定标识符与计算机内存中的特定位置联系起来，同时确定了储存在某位置的信息类型或数据类型。


