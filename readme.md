# **16 de Noviembre del 2022**
## Git + Markdown

Comandos

#### **Markdown**

"#" Encabezado nivel 1

"##" Encabezado nivel 2


"###" Encabezado nivel 3

"####" Encabezado nivel 4

"#####" Encabezado nivel 5

"######" Encabezado nivel 6

# **18 de Noviembre del 2022**
# Intro to C
Primer Hola Mundo

> code
```c
#include <stdio.h>

void main()
{
    printf("Hola Cris!\n");
}
```

# **21 de Noviembre del 2022**
# Compilador C
### El compilado de C hace un analisis sintatico y semantico

```c
int
printf
scant
etc
void (Procedimiento)
```
# **22 de Noviembre del 2022**
# Programa numero mayor o igual en C

```c
#include <stdio.h>

void main()
{
    int n1,n2;

    printf("\nIngrese el primer numero: ");
    scanf("%d", &n1);
    printf("\nIngrese el segundo numero: ");
    scanf("%d", &n2);

    if (n1>n2)
       printf("\nEl numero mayor es el: %d", n1);
    else
    if (n1<n2)
       printf("\nEl numero mayor es el: %d", n2);
    else
       printf("\nLos numeros son iguales");
}
```
# **06 de Diciembre del 2022**
# Determinar el Area de un Rectangulo
```c
#include <stdio.h>

/**
* @author: Cris
* @date: 6.dic.2022
* @details: Determinar el area de un rectangulo
*/
int main()
{   //Declarar e inicializar variables
    int longitud=0, ancho=0, areaRect=0;
    printf("Ingrese la Longitud: ");
    scanf("%i", &longitud);

    printf("Ingrese el Ancho: ");
    scanf("%i", &ancho);

    areaRect= longitud * ancho;

    printf("El Area del Rectangulo es: %i \n",areaRect);
    printf("El Area del Rectangulo de Ancho %i y Longitud %i es: %i \n",ancho, longitud, areaRect);

    return 0;
}
```
