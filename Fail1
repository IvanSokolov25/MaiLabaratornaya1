#include <stdio.h>
#include <math.h>
int main()
{
    int a;
    int b;
    int stepen;
    printf("Введите x:\n");
    scanf("%i",&a);
    printf("Введите y:\n");
    scanf("%i",&b);
        int summa;
        summa=a+b;
        printf("Их сумма равна %d\n",summa);
        printf("Введите желаемую степень\n");
        scanf("%i",&stepen);
        int s=pow(summa,stepen);
        printf("Сумма x и y в вашей степени равна %i\n",s);
        float drob;
        float ostatok;
            if (b==0)
                printf("Y меньше 0. Меня не проведёшь \n");
                else
                {
                     ostatok= b%a;
                    printf("Остаток равен %f\n",ostatok);
                    if(ostatok==0)
                       {printf("Остаток меньше нуля\n");
                        printf("%lu",sizeof (s));}
                    else
                    {
                        drob=s/ostatok;
                        printf("Степень разделить на остаток равно %f\n",drob);
                    }
                }
    return 0;
}
