#include <stdio.h>

int main(void) 
{
    int dan, i = 0;
    printf("단수 입력: ");
    scanf("%d", &dan);

    for(i=1; i <= 9; i++) {
        printf("%d * %d = %d\n", dan, i, dan * i); 
    }
}
