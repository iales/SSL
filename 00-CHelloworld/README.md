# 00-CHelloWorld

Programa que imprime `Hello, World!` en la terminal.

## Archivos

- `hello.c`: Código fuente del programa en C.

- `a.exe`: se creo al ejecutar "cc hello.c"

- `output.txt`: Archivo con la salida generada al ejecutar el programa.
                (Para guardar el contenido en output.txt se ejecuto ./a> output.txt en la terminal )
## Compilador
GCC "GNU Compiler Collection"

## Para verificar el estandar de C, se Uso:
echo | gcc -dM -E -x c - | grep __STDC_VERSION__
#define __STDC_VERSION__ 201710L
