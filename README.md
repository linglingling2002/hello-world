#include <stdio.h>

int main()
{
    int price = 0;

    printf("please write price（yuan）：");
    scanf("%d", &price);

    int change = 100 - price;

    printf("change %d yuan。\n", change);

    return 0;
}
