# Capítulo 1: Introducción a C

## 1.1 ¿Qué es C?

C es un lenguaje de programación de propósito general creado en los años 70 por Dennis Ritchie en los Laboratorios Bell. Es un lenguaje estructurado, eficiente y portátil que permite trabajar cerca del hardware, y es la base de muchos sistemas operativos y software de sistemas.

### Características principales

- Lenguaje compilado y de bajo nivel.
- Permite manipulación directa de memoria.
- Código eficiente y rápido.
- Portabilidad entre diferentes plataformas.
- Base para lenguajes modernos (C++, C#, Java).

---

## 1.2 Estructura básica de un programa en C

```c
#include <stdio.h> //Incluye la biblioteca estándar para entrada/salida

int main() { // Función principal, punto de entrada del programa
    printf("Hola, mundo\n"); // Muestra texto en pantalla
    return 0; // Finaliza el programa indicando exit
}


```

## 1.3 Compilación y ejecución

- Guardar el código en un archivo con extensión .c
- Compilar con ` gcc hola.c -o hola`
- Ejecutar con ./hola(Linux/macOS) o hola.exe (Windows)

## 1.4 Buenas prácticas

- Usa comentarios para explicar tu código
- Mantén una indentación clara.
- Usa nombres descriptivos para variables y funciones
- Divide tu código en funciones pequeñas y reutilizables

## Ejercicios

1. Modifica el programa para que imprima tu nombre y tu ciudad
2. Escribe un programa que imprima tres lineas con mensajes distintos
3. Elimina un punto y coma y observa qué error da el compilador.
4. Imprime un poema o una cita que te guste.
