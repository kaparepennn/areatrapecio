#include <stdio.h>

int main()
{

    float b, B, a, area;
    
    printf("Buen día. Por favor ingrese el valor de la base superior del trapecio:\n ");
    scanf("%f", &b);
    
    printf("Ahora ingrese el valor de la base inferior del trapecio:\n ");
    scanf("%f", &B);
    
    printf("Por último ingrese el valor de la altura del trapecio:\n ");
    scanf("%f", &a);
    
    //Lógica del programa
    
    area= ((b + B) *a) /2;
    printf("Este es el área del trapecio: %.2f\n", area);
    
    return 0;
}