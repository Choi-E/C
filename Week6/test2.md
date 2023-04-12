#include <stdio.h>
// #define _CRT_SECURE_NO_WARNINGS

int plusFunc (int x, int y) 
{
    return x + y;
}

int main(void)
{
    int x;
    int y;
    int sum;
    
    printf("첫번째 숫자를 입력하세요 : ");
    scanf("%d", &x);
    printf("두번째 숫자를 입력하세요 : ");
    scanf("%d", &y);

    sum = plusFunc(x, y);
    printf("두 수의 합은 = %d\n", sum);

    return 1;
}
