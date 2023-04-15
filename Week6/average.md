//평균 계산기


------------------------
#include <stdio.h>

int main(void)
{
    int grade, n;
    float sum, average;

    //필요한 변수들을 초기화한다.
    n = 0;
    sum = 0;
    grade = 0;

    printf("성적 입력을 종료하려면 음수를 입력하시오\n");
    //성적을 입력받아서 합계를 구하고 학생 수를 센다.
    while(grade >= 0)
    {
        printf("성적을 입력하시오: ");
        scanf("%d", &grade);

        sum += grade; // sum = sum + grade - 1 도 가능
        n++;
    }

    sum = sum - grade;
    n--;

    average = sum / n;
    printf("성적의 평균은 %f입니다.\n", average);

    return 0;
}

----------------------------
