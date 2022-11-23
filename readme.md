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

int main()
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
    return 0;
}
```
