int main()
{
    //Crear un programa que permita calcular el area de un trapecio. El programa debe pedir al usuario los datos básicos necesarios y hacer el calculo.
    
    //Declaramos variables
    int b, B;
    float area;
    
    printf("Buen día, por favor ingrese los valores del trapecio:\n ");
    scanf("%d%d", &b, &B);
    
    area=(b+B)/2;
    printf("\narea=%f", area);
    
    return 0;

}
