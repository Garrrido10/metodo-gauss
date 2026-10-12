# Métodos Numéricos - Sistemas de Ecuaciones Lineales

Este repositorio contiene las implementaciones en Java desarrolladas bajo un enfoque modular para la resolución de sistemas de ecuaciones lineales.

---

## Práctica 1: Método de Eliminación Gaussiana
Implementación del método numérico de eliminación gaussiana con pivoteo parcial y sustitución regresiva.

### Estructura modular:
- **`Gauss.java`**: Contiene la lógica para la triangulación superior de la matriz aumentada.
- **`Lanzador_gaus.java`**: Clase ejecutable con el método `main` para probar la eliminación gaussiana.

### Pasos para compilar y ejecutar:
1. Abre tu proyecto en IntelliJ IDEA.
2. Ejecuta el archivo **`Lanzador_gaus.java`**.

---

## Práctica 2: Método de Gauss-Jordan
Implementación del método de Gauss-Jordan reutilizando el módulo de triangulación superior previo para transformar la matriz aumentada directamente en una matriz identidad y obtener el vector de soluciones de manera directa.

### Estructura modular:
- **`Gauss.java`**: Módulo reutilizado de triangulación superior.
- **`GaussJordan.java`**: Contiene la lógica de normalización de pivotes y barrido superior.
- **`Lanzador_GaussJordan.java`** (o `Main.java`): Clase ejecutable para probar el método.

### Pasos para compilar y ejecutar:
1. Asegúrate de tener los archivos `Gauss.java`, `GaussJordan.java` y tu clase lanzadora en la carpeta `src`.
2. Haz clic derecho sobre tu clase lanzadora y selecciona **Run**.

### Ejemplo de prueba y salida en consola:
```text
=== SOLUCIÓN DEL SISTEMA ===
x1 = 2.0000
x2 = 3.0000
x3 = -1.0000
