# c
//two_func.c 含有两个函数
#include <stdio.h>
void butler(void);//ANSI/ISO C函数原型
int main(void)
{
	printf("I will summon the butler function.\n");
	butler();
	printf("Yes. Bring me some tea and writeable DVDs.\n");

	getchar();

	return 0;

}
void butler(void)//函数定义开始
{
	printf("You rang,sir?\n");
}


butler（）在上述代码中出现三次
第一次是函数原型，告知编译器在程序中要使用该函数；（函数原型是一种声明形式，告知编译器正在使用某函数，因此也叫函数声明）
第二次是函数调用，出现在main（）中
第三次是定义这个函数
我们定义函数时 一定要在名字前面注明显示类型[例如int xxx （）] 这里没有返回值所以说是 void butler
（补充：定义这个函数的时候没有return 因为我们加了void 没有返回值 也就是说不用return 若是int之类的表示返回数字类型的 一定要加return)
括号中的void是说butler不带参数 这里的void表示的是“空的”而不是“无效”
在main中调用时直接写出函数名和括号即可
定义的函数与main函数的顺序：
它们的顺序不会改变程序的执行顺序，main（）函数是程序的入口 何时执行butler函数取决于它在main（）中的位置
C的惯例是把main放在开头的，因为它提供了程序的基本框架
注：printf函数的函数原型在stdio.h文件中 因此没有在开头做函数声明。
