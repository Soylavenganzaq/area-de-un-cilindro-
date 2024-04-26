# area-de-un-cilindro-
trabajo laboral


#include <stdio.h>
#define PI 3.14


int main() {
    float altura, area, radio;

    printf("Ingresa el valor de la altura: ");
    scanf("%f", &altura);


    printf("Ingresa el valor del radio: ");
    scanf("%f", &radio);
   
   
    area = 2*PI*radio*(radio + altura)+(2*PI*radio*radio);
    
    printf("El area total del cilindro es: %.2f\n", area);

    return 0;

   
}
