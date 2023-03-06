# Lista-Aeds1

5-


#include <stdio.h>
#include <math.h>


int main()
{
    int num;
    int cubo;
    int raizquad;
    float raizcubica;
    float seno;
    float coseno;
    printf("Escolha um Numero para a transformação ---> ");
    scanf("%d", &num);
    
    cubo = pow (num,3);
    raizquad = sqrt(num);
    raizcubica = cbrt(num);
    seno = sin (num);
    coseno = cos (num);
    
    printf("Elevado ao Cubo: de %d sera %d", num, cubo);
    printf("\n Raiz Quadrada: de %d sera %d", num, raizquad);
    printf("\n Raiz Cubica: de %d sera %f", num, raizcubica);
    printf("\n Seno: de %d sera %f", num, seno);
    printf("\n Coseno: de %d sera %f", num, coseno);
    

    return 0;
}


6- 


#include <stdio.h>
#include <math.h>


int main()
{
    int num1;
    int num2;
    float res;
    printf("Digite o Primeiro Valor inteiro ---> ");
    scanf("%d", &num1);
    
    printf("\n Digite o Segundo Valor inteiro ---> ");
    scanf("%d", &num2);
    
   res = num1 / num2;
    
    printf("\n O resto da divisao entre %d e %d sera %f", num1, num2, res);
    return 0;
}

7-

#include <stdio.h>
#include <math.h>


int main()
{
    
    int base;
    int altura;
    int perimetro;
    int area;
    
    printf("\n Digite o Valor da base do retangulo ---->  ");
    scanf("%d", &base);
    
    printf("\n Digite O Valor da Altura ----> ");
    scanf("%d", &altura);
    
    area = base * altura;
    perimetro = 2 * (base + altura);
    
    printf("\n O valor da area sera %d", area);
    printf("\n O Valor do perimetro sera %d", perimetro);
    
    return 0;
}

8 - 


#include <stdio.h>
#include <math.h>


int main()
{
    int basemaior;
    int basemenor;
    int altura;
    int area;
    
 
    printf("\n Digite o Valor da Base Maior ------>  ");
    scanf("%d", &basemaior);
    
    printf("\n Digite o Valor de Base Menor ------>  ");
    scanf("%d", &basemenor);
    
    printf("\n Digite o valor de Altura -----> ");
    scanf("%d", &altura);
    
    area = (basemaior + basemenor) * altura / 2;
    
    printf("\n A area Do trapezio sera %d", area);
    
    return 0;
}

