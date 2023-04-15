// n 이하의 모든 짝수의 합 구하기
// sum1.md 변형

--------------------------

#include <stdio.h>

int main(void)
{
    int i, n, sum;

    printf("정수를 입력하쇼: \n");
    scanf("%d", &n);

    i = 0;
    sum = 0;

    while(i <= n)
    {
        sum += i;
        i = i + 2;          // i += 2;로 해도 됨!
    }

    printf("1부터 %d까지의 합은 %d입니다\n", n, sum);
    return 0;
}


--------------
