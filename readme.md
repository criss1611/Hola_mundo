# **16 de Noviembre del 2022**

```
# GitHub

Git hub es considerada una de las herraminetas mas importantes para cualquier desarrollador de software orifesional que quiera mejroar su flujo de trabajo y colaboración.


># Git


Git o Git Bash es una conjunto de proframas diseñados para ejecutarse en una terminal.

>## Comandos Git

    pwd --> En que directorio estoy
    ls --> En que carpeta me encuentro
    git init --> Empezar el seguimiento de git
    git add . --> Agregar todos nuestros archivos 
    git status --> Estado de nuestro seguimiento
    git add index.html --> Agregar archivo personalizado
    echo [archivo] >> .gitignore --> Ignorar un archivo
    git status
    echo .gitignore >> .gitignore --> Ignorarse a si­ mismo
    cat index.html --> Que se encuentra dentro de mi archivo

># IDE Visual Studio Code


VSCode es un entorno de escritura de código con el cual se pueden trabajar diferentes lenguajes como lo son:

- C/C++
- C#
- Python
- JavaScript
- HTML/CSS
- Java GUI
- Java

... y más.

También, se pueden instalar diferentes extensiones que pueden servir para complementar los lenguajes, las terminales y estos pueden hacer el trabajo más dinamico y eficiente.

># Markdown


Markdown es un formato que nos permite crear archivos html y xml usando una sintaxis bastante clara y sencila de escribir. Todo archivo tipo Markdown debe tener una termianción " .md".

Ejem: "Programación1.md; Hello.md; asasssssdad.md"

>## Títulos

Para dar formato de título o subtitulo a una línea, se debe empezar con # (Máximo 6 caracteres de este tipo) seguido de un espacio:

- Nivel 1: #
# H1

- Nivel 2: ##
## H2

- Nivel 3: ###
### H3

- Nivel 4: ####
#### H4

- Nivel 5: #####
##### H5

- Nivel 6: ######
###### H6

>## Formatos

Se usan diferentes simbolos, dependiendo del tipo de ofrmato que se quiera usar en el texto, en este caso no es necesario el uso de espacios entre símbolo y caracter:

- Cursiva   * *

*EJEMPLO DE CURSIVA*

- Negrita   ** **
  
**EJEMPLO DE NEGRITA**

- Tachado   ~~ ~~

~~EJEMPLO DE TACHADO~~

>## Marco Obscuro}

Para enmarcar un texto, usamos la tecla "Tab" para cierta linea o parrafos.

    Cupidatat irure enim deserunt labore nisi consectetur amet. Pariatur exercitation reprehenderit pariatur ea aliquip. Voluptate esse quis voluptate excepteur pariatur laboris voluptate aliquip dolore aliquip. Aute dolor sit minim ea esse ad non reprehenderit occaecat veniam.

>## Listas ordenadas y desordenadas

Para listas desordenadas, usamos "*" al principio de la linea para enmarcar un item, asi como tambien sub-items al ir a nueva linea, realizando "Tab" y repitiendo los primeros pasos.

* obj1
    * subobj1
* obj2
    * suboj2
* objn
    subobjn

en listas ordenadas ponemos "n. item" para manterner una cierta jerarquia.

1. obj1
2. obj2
3. objn

>## Hipervínculos

[youtube.com](https://www.youtube.com/watch?v=ARWg160eaX4)

[youtube.com](https://www.youtube.com/watch?v=dQw4w9WgXcQ "No lo hagas")

>## Lineas divisoras
"---"
"___"
___
---


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
>## Insertar códigos

`console.log('hello world')`

Inseramos los caracteres ``` antes de escribir nuestro código, si queremos que se vea omo se muestre en nuestro editor de código, debemos especificar el tipo de lenguaje se usa:
```c
#include <stdio.h>

//Comentario en una sola línea

/*	Este
	es
	un
	comentario
	multilineal
*/

int main(){
	
	printf("Hello Cris!\n");
	printf("I like play videogames\n");
	printf("It's really good\n");

	printf("\nAhora vienen los comentarios y secuencia de escapes\n");

/*	Secuencia de escape: Combinación de caracteres constitiendo en \
	y una letra o combinacion de dígitos.
	Especifican acciones en una línea o string de texto.
	\n = nueva línea
	\t = tab
*/
	printf("\n1\t2\t3\n4\t5\t6\n7\t8\t9\n");
	printf("\"Me encantan los videojuegos\" - Fortnite me gusta mucho");
	return (0);
}
```

```cpp
#include <iostream>

int main(int argc, char *argv[])
{
	std::cout << "Hello Cris!" << std::endl;
}
```

>## Insertar imágenes

>### Imágenes de internet

![VisualStudioCodeLogo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/512px-Visual_Studio_Code_1.35_icon.svg.png?20210804221519 "VSCode Logo")

>### Imágenes Locales
![EjemploLogo](ejemplo.jpg "steam cromos")

>## Emojis

@faztweb :smiley: :+1:

# **21 de Noviembre del 2022**
# Compilador C
### El compilado de C hace un analisis sintatico y semantico

21 de noviembre del 2022

```c
#include <stdio.h>

int main(){
    /*  Variables: Espacios de la memoria dedicados para almacenar un valor.
        Se refiere al nombre de una variable para tener acceso al valor almacenado.
        Dicha variable ahora se comporta como su fuese el valor que contiene.
        PERO debemos declarar el tipo de variable que se está almacenando.
    */
    int x;      //declaración
    x=123;      //inicialización
    int y=456;  //declaración + inicialización

    int edad = 18;          //integer
    float dinero = 8.50;    //número con décimales
    char calificacion = 'F';//único caracter
    char nombre[] = "Cris";//array de caracteres

    printf("\nHola %s,\n",nombre);
    printf("Tienes %i años,",edad);
    printf(" un promedio de %c en programación ",calificacion);
    printf("y tienes alrededor de %f dólares en tu cuenta.\n", dinero);

    printf("\n|Ahora, Operaciones \"Mayor o igual que\":\n");

    int a=10, b=20;

    printf("\nIntroduce dos enteros separados por un espacio: \n");
    scanf("%i %i", &a, &b);

    if (a > b)
        printf("El mayor es %i", a);
    
    if (b > a)
            printf("El mayor es %i", b);

    if (b == a)
            printf("a y b son iguales");

    printf("\n");

    return 0;
}
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
``
># Arrays
13 de diciembre del 2022

```c
#include <stdio.h>

int main(){
    int l;
    printf("\nIngrese la medida del cuadrado:");
    scanf("%i", &l);
    for (int c = 1; c <= l; c++)
    {
        for (int f = 1; f <= l; f++)
        {
            if (f%2==c%2){
                printf(" + ");
            }
            else{
                    printf(" - ");
                }
            
        }
        printf("\n");
    }
    
    printf("\nEl cuadrado mide %i\n", l);

    return 0;
}
```
