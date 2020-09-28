# Corriente
//REALIZADO: Brayan Alexis Rojas Mila
//26/09/2020
#include <stdio.h>

int main ()
{
    float V;
    int R1, R2, R3;
    float I1, I2, I3;

    printf ("DAME EL VALOR DE LA FUENTE V: ");
    scanf ("%f",&V);

    printf("EL VALOR DEBE SER ESCRITO EN NOTACION COMPLETA NO USAR PREFIJOS\n");
    printf("RESISTENCIA1; ");
    scanf("%d",&R1);

    printf("RESISTENCIA2: ");
    scanf("%d", &R2);

    printf("RESISTENCIA3: ");
    scanf("%d", &R3);
    I1= V/R1;
    I2= V/R2;
    I3= V/R3;
    printf("LA CORRIENTE I1 ES %0.3fA\n",I1);
    printf("LA CORRIENTE I2 ES %0.3fA\n",I2);
    printf("LA CORRIENTE I3 ES %0.3fA\n",I3);
    printf("EL VOLTAJE EN R1 ES %0.3fV\n", V);
    printf("EL VOLTAJE EN R2 ES %0.3fV\n", V);
    printf("EL VOLTAJE EN R3 ES %0.3fV\n", V);
}
