# Método de Gauss

## Lenguaje utilizado

Java

## Descripción

Programa que resuelve un sistema de ecuaciones lineales utilizando el método de Eliminación Gaussiana.

El programa realiza primero la eliminación gaussiana para convertir la matriz en una matriz triangular superior y después utiliza sustitución regresiva para obtener las soluciones.

## Archivos del programa

- `Gauss.java`: contiene los métodos para realizar la eliminación gaussiana y la sustitución regresiva.
- `defmatrizz.java`: contiene la matriz aumentada utilizada como ejemplo.
- `Lanzador_gaus.java`: contiene el método principal y se encarga de ejecutar el programa y mostrar los resultados.

## Pasos para ejecutar el programa

1. Abrir el proyecto en IntelliJ IDEA.
2. Abrir el archivo `Lanzador_gaus.java`.
3. Ejecutar el método `main`.
4. Revisar en la consola las soluciones del sistema.

## Ejemplo de prueba

Matriz utilizada:

```text
3.0   -0.1   -0.2    7.85
0.1    7.0   -0.3  -19.3
0.3   -0.2   10.0   71.4