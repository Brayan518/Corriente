//REALIZADO POR BRAYAN ALEXIS ROJAS MILA
//26/09/2020
//01_CIRCUITO

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




//REALIZADO: BRAYAN ALEXIS ROJAS MILA 
//26/09/2020 
//02_LEDS 

#include <stdio.h>
//FORMULA1: I = V/R //FORMILA2: R = V / I

int main (){ 
float V,R1,R2,R3;


printf("DAME EL VALOR DEL VOLTAJE: ");
scanf("%f",&V);

R1=V/0.02;
R2=V/0.015;
R3=V/0.02;

printf("EL RESULTADO DE LA RESISTENCIA ROJO BRILLANTE ES %f \n", R1);

printf("EL RESULTADO DE LA RESISTENCIA AMARRILLO STD ES %f \n", R2);

printf("EL RESULTADO DE LA RESISTENCIA BLANCO ES %f \n", R3);

return 0;
}




// REALIZADO POR BRAYAN ALEXIS ROJAS MILA
// 03/10/2020
// 03_CALIFICACIONES
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int C1, C2, C3, C4, C5, CO;
    char CALIF1, CALIF2, CALIF3, CALIF4, CALIF5;

    printf ("INGRESA LA PRIMERA CALIFICACION: \n");
    scanf ("%c", & CALIF1);
    printf ("INGRESA LA PRIMERA CALIFICACION: \ n");
    fflush (stdin);
    scanf ("%c", & CALIF2);
    printf ("INGRESA LA PRIMERA CALIFICACION: \ n");
    fflush (stdin);
    scanf ("%c", & CALIF3);
    printf ("INGRESA LA PRIMERA CALIFICACION: \n");
    fflush (stdin);
    scanf ("%c", & CALIF4);
    printf ("INGRESA LA PRIMERA CALIFICACION: \n");
    fflush (stdin);
    scanf ("%c", & CALIF5);


    if (CALIF1 == 'A' || CALIF1 == 'a')
    {
      C1= 10;
    }
    else if (CALIF1 == 'B' || CALIF1 == 'b')
    {
     C1=9;
    }
    else if (CALIF1 == 'C' || CALIF1 == 'c')
    {
      C1=8;
    }
    else if (CALIF1 == 'D' || CALIF1 == 'd')
    {
      C1=7;
    }
    else if (CALIF1 == 'E' || CALIF1 == 'e')
    {
      C1=6;
    }
    else if (CALIF1 == 'F' || CALIF1 == 'f')
    {
      C1=5;
    }


    if (CALIF2 == 'A' || CALIF2 == 'a')
    {
      C2=10;
    }
    else if (CALIF2 == 'B' || CALIF2 == 'b')
    {
      C2=9;
    }
    else if (CALIF2 == 'C' || CALIF2 == 'c')
    {
      C2=8;
    }
    else if (CALIF2 == 'D' || CALIF2 == 'd')
    {
      C2=7;
    }
    else if (CALIF2 == 'E' || CALIF2 == 'e')
    {
      C2=6;
    }
    else if (CALIF2 == 'F' || CALIF2 == 'f')
    {
      C2=5;
    }


    if (CALIF3 == 'A' || CALIF3 == 'a')
    {
      C3=10;
    }
    else if (CALIF3 == 'B' || CALIF3 == 'b')
    {
     C3=9;
    }
    else if (CALIF3 == 'C' || CALIF3 == 'c')
    {
      C3=8;
    }
    else if (CALIF3 == 'D' || CALIF3 == 'd')
    {
      C3=7;
    }
    else if (CALIF3 == 'E' || CALIF3 == 'e')
    {
      C3=6;
    }
    else if (CALIF3 == 'F' || CALIF3 == 'f')
    {
      C3=5;
    }


    if (CALIF4 == 'A' || CALIF4 == 'a')
    {
      C4=10;
    }
    else if (CALIF4 == 'B' || CALIF4 == 'b')
    {
     C4=9;
    }
    else if (CALIF4 == 'C' || CALIF4 == 'c')
    {
      C4=8;
    }
    else if (CALIF4 == 'D' || CALIF4 == 'd')
    {
      C4=7;
    }
    else if (CALIF4 == 'E' || CALIF4 == 'e')
    {
      C4=6;
    }
    else if (CALIF4 == 'F' || CALIF4 == 'f')
    {
      C4=5;
    }


    if (CALIF5 == 'A' || CALIF5 == 'a')
    {
      C5=10;
    }
    else if (CALIF5 == 'B' || CALIF5 == 'b')
    {
     C5=9;
    }
    else if (CALIF5 == 'C' || CALIF5 == 'c')
    {
      C5=8;
    }
    else if (CALIF5 == 'D' || CALIF5 == 'd')
    {
      C5=7;
    }
    else if (CALIF5 == 'E' || CALIF5 == 'e')
    {
      C5=6;
    }
    else if (CALIF5 == 'F' || CALIF5 == 'f')
    {
      C5=5;
    }
    CO=(C1+C2+C3+C4+C5)/5;
    printf ("EL PROMEDIO ES: %d", CO);

    return 0;
 }




// REALIZADO POR BEAYAN ALEXIS RPJAS MILA
// 03/10/2020
// 04_ECUACIÓN
#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main ()
{
    int x1, x2, a, b, c;
    
   printf ("INGRESA LA PRIMERA VARIABLE: \n");
    scanf ("%lf", &a);
    printf ("INGRESA LA SEGUNDA VARIABLE: \n");
    fflush (stdin);

    scanf ("%lf", &b);
    printf ("INGRESA LA TERCER VARIABLE: \n");
    fflush (stdin);
    
    scanf ("%lf", & c);
     x1 = ((- b + sqrt (pow (b, 2) - (4 * a * c))) / (2 * a));
     x2 = ((- b-sqrt (pow (b, 2) - (4 * a * c))) / (2 * a));

    printf ("EL VALOR DE  x1 ES: %lf \n", x1);
    printf ("EL VALOR DE x2 ES: %lf \n", x2);
    
    return 0;
}
