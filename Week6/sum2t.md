// //n 이하의 모든 짝수의 합을 구하는 것


--------------

#include <stdio.h>

int main(void)
{
    int n, sum = 0, i = 1;

    printf("정수를 입력하쇼: ");
    scanf("%d", &n);

    while(i <= n)
    {
        if(i % 2 == 0)
        {
            sum += i;
        }
            i++;
    }
    printf("1부터 %d까지의 짝수합은 %d입니다\n", n, sum);
    return 0;
}

--------------------
