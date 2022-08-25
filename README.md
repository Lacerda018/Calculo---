# Calculo---

#include <stdio.h>

int main()
{
    int num,x;
    char o;

    printf("informe um numero");
    scanf("%d", &num);

    printf("informe a operacao  que deseja fazer:\n");
    printf("[+,-]");
    scanf(" %c", &o);
    printf("informe um numero");
    scanf("%d", &x);
    
        if (o == '+'){
            printf("o resultado e: %d",(num+x));
        }else{
            printf("o resultado e: %d",(num-x));
        }
    return 0;
}
