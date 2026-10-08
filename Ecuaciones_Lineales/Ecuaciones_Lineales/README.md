# Método de Gauss - Sistemas de Ecuaciones Lineales

Implementación en Java del método numérico de Eliminación Gaussiana simple con sustitución regresiva, desarrollado bajo un enfoque modular.

## Lenguaje de programación
* **Java** 
## Pasos para compilar y ejecutar el programa

1. Asegúrate de tener instalado el **JDK de Java** en tu computadora.
2. Abre tu terminal o consola y dirígete a la carpeta raíz del proyecto.
3. Compila los archivos fuente ejecutando el siguiente comando:
   ```bash
   javac Ecuaciones_lineales/defmatrizz.java Ecuaciones_lineales/Gauss.java Ecuaciones_lineales/Lanzador_gaus.java

 ## Ejemplo de prueba y salida por consola
### Matriz de entrada (Aumentada [A | b]):
* Fila 1: `3.0x1 - 0.1x2 - 0.2x3 = 7.85`
* Fila 2: `0.1x1 + 7.0x2 - 0.3x3 = -19.3`
* Fila 3: `0.3x1 - 0.2x2 + 10.0x3 = 71.4`

### Salida esperada en consola:
```text
Soluciones del sistema:
x1 = 3.0
x2 = -2.5
x3 = 7.0
