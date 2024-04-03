# Ejemplo de Herencia en C++

Este repositorio contiene un ejemplo de cómo usar herencia en C++ con una clase base `String` y una clase derivada `String_Numerico`.

## Explicación del código

El archivo `herencia_ejemplo.cpp` contiene un programa que demuestra el uso de herencia en C++. Aquí hay una breve explicación del código:

- Se define una clase base `String` que representa una cadena de caracteres. Esta clase proporciona métodos para inicializar, asignar, concatenar y imprimir cadenas de caracteres.
- Se define una clase derivada `String_Numerico` que hereda de la clase base `String`. Esta clase está especializada para manejar cadenas que representan números.
- En la función `main`, se crean instancias de las clases `String` y `String_Numerico` para demostrar su uso.
- Se imprime el contenido de las instancias creadas utilizando el método `Imprimir` de cada clase.

## Cómo compilar y ejecutar el código

Para compilar y ejecutar el programa, sigue estos pasos:

1. Asegúrate de tener un compilador de C++ instalado en tu sistema.
2. Coloca el archivo `herencia_ejemplo.cpp` en un directorio.
3. Abre una terminal y navega hasta el directorio que contiene el archivo.
4. Compila el código ejecutando el siguiente comando:
   ```
   g++ -o herencia_ejemplo herencia_ejemplo.cpp
   ```
5. Una vez compilado, ejecuta el programa con el siguiente comando:
   ```
   ./herencia_ejemplo
   ```

Esto imprimirá el resultado del programa en la terminal.



