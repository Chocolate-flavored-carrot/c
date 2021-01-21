# c
1.语法错误
#include <stdio.h>
int main(void)
{//函数体里面每条语句最后都要加;
    int n, n2, n3; //多个声明不要写成 int n, int n2, int n3

    n = 5;
    n2 = n * n;
    n3 = n2 * n2;
    printf("n=%d,n squared=%d, n cubed=%d\n", n, n2, n3);

    getchar();

    return 0;
}

//nogood.c 有错误的程序
#include <stdio.h>
int main(void)
（
   int n, int n2, int n3
   n=5;
   n2=n*n;
   n3=n2*n2；
   printf("n=%d,n squared=%d, n cubed=%d\n", n, n2, n3)
   
   return 0;
）

