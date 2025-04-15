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
Version de C que compila: hasta C2x inclusive

## Para verificar el estandar de C, se Uso:
Para verificar hasta que version de C compila:

Abri una terminal y empece a probar diversas versiones de C mediante el comando "gcc -std=(version de c a probar) hello.c -o hello.exe" hasta llegar a la version c23, tambien conocida como C2x.
Como fui capaz de ejecutar "gcc -std=c23 hello.c -o hello.exe" sin problemas, y sin recibir errores, pude concluir que hasta esa version podia compilar.
