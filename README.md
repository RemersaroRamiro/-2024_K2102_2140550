# -2024_K2102_2140550
Ejercicios:
2. 
La funcion "printf" se utiliza para escribir la salida en consola.
La funcion "scanf" se utiliza para leer datos de la entrada estándar (generalmente el teclado)
Cuenta con varios especificadores de formato que inician con "%", estos son:
%c -> Un solo caracter
%i -> Un dato entero
%d -> Un dato decimal
%f -> Un dato decimal simple
%s -> Cadena de caracteres
%e -> Un dato decimal exponencial
%o -> Un dato octal
%x -> Un dato hexadecimal

3. 
#include <stdio.h>
int main()
{
    printf("Hola Mundo");
    return 0;
}
4.
#include <stdio.h>
int main()
{
    char nombre[50];
    printf("Ingrese nombre completo: ");
    scanf("%s", nombre);
    printf("\nHola %s ", nombre);
    return 0;
}
5. Si, tuve que declarar la variable "nombre" siendo una cadena de caracteres.
6. En Algoritmos y Estructuras de datos se utilizaria "cout" y "cin" para trabajar con el ingreso e impresion de datos.
