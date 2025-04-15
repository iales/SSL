# 00-CHelloWorld

Programa que imprime `Hello, World!` en la terminal.

## Archivos

- `hello.c`: Código fuente del programa en C.

- `a.exe`: se creo al ejecutar "cc hello.c"

- `output.txt`: Archivo con la salida generada al ejecutar el programa.
                (Para guardar el contenido en output.txt se ejecuto ./a> output.txt en la terminal )
## Compilador
GCC "GNU Compiler Collection"

version: 14.2.0

Version de C que compila: c17 hasta c18 inclusive

## Para verificar el estandar de C, se Uso:
$ echo | gcc -dM -E -x c - | grep __STDC_VERSION__

#define __STDC_VERSION__ 201710L
 
 201710L Significa C17 (ISO/IEC 9899:2018) 

Para verificar:

Abri una terminal y empece a probar diversas versiones de C mediante el comando "gcc -std=(version de c a probar) hello.c -o hello.exe" hasta llegar a la version c18.

Como fui capaz de ejecutar "gcc -std=c18 hello.c -o hello.exe" sin problemas, y sin recibir errores, pude concluir que hasta esa version podia compilar.
