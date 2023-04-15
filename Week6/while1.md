#include <stdio.h>

int main()
{
    int i = 1;

    while(1)
    {
        printf("%d * %d = %d\n", 2, i, 2*i);
        i++;
        if(i>9)
        {
            break;            //if(i>9)랑 break;가 없으면 무한 반복 
        }
    }
}
