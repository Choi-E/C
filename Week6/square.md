// while문을 이용한 제곱값 출력 프로그램



-----------
#include <stdio.h>

int main(void)
{
    int n;

    printf("==============\n");
    printf("       n       n의 제곱 \n");
    printf("==============\n");

    n=1;
    while (n <= 10)
    {
        printf("%d     %d\n", n, n*n);
        n++;
    }

    return 0;
}

-----------
