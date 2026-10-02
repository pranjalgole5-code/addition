#include <stdio.h>

int main()
{
    int a, b, sum;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    sum = a + b;

    if (sum >= 0)
    {
        printf("Sum = %d", sum);
    }
    else
    {
        printf("Sum is negative = %d", sum);
    }

    return 0;
}
