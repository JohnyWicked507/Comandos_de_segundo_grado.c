# Comandos_de_segundo_grado.c
#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main(){

    int a, b, c;
    float x1, x2;

    printf("Valor de a: ");
    scanf("%d", &a);
    printf("Valor de b: ");
    scanf("%d", &b);
    printf("Valor de c: ");
    scanf("%d", &c);

    x1 = (-b + sqrt(pow(b, 2)-(4*a*c)))/(2*a);
    x2 = (-b - sqrt(pow(b, 2)-(4*a*c)))/(2*a);

    printf("Valor de x1: %.2f \n", x1);
    printf("Valor de x2: %.2f", x2);


    return 0;
}
