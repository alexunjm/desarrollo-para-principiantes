# Capítulo 2

## Condicionales

En este capítulo, exploraremos cómo utilizar las estructuras de control condicional en JavaScript, incluyendo el uso de la estructura if-else para tomar decisiones, los operadores de comparación en condicionales y cómo trabajar con condicionales anidados.

1. Uso de la estructura if-else para tomar decisiones

    La estructura if-else permite tomar decisiones en base a una condición booleana.

    La sintaxis básica del if-else es:

    ```javascript
    if (condicion) {
        // Código a ejecutar si la condición es verdadera
    } else {
        // Código a ejecutar si la condición es falsa
    }
    ```

    El bloque de código dentro del if se ejecuta solo si la condición es verdadera. Si la condición es falsa, el bloque de código dentro del else se ejecuta en su lugar.

2. Uso de operadores de comparación en condicionales

    Los operadores de comparación se utilizan para comparar valores y producir un resultado booleano.

    Algunos operadores de comparación comunes incluyen:
    - Igualdad (==): verifica si dos valores son iguales.
    - Desigualdad (!=): verifica si dos valores son diferentes.
    - Mayor que (>): verifica si un valor es mayor que otro.
    - Menor que (<): verifica si un valor es menor que otro.
    - Mayor o igual que (>=): verifica si un valor es mayor o igual que otro.
    - Menor o igual que (<=): verifica si un valor es menor o igual que otro.

3. Condicionales anidados

    Los condicionales anidados permiten tener múltiples bloques de código condicionalmente ejecutables.

    Se pueden utilizar condicionales if-else dentro de otros condicionales if-else para establecer condiciones adicionales.

    Ejemplo de condicional anidado:

    ```javascript
    if (condicion1) {
        // Código a ejecutar si condicion1 es verdadera

        if (condicion2) {
            // Código a ejecutar si condicion2 también es verdadera
        } else {
            // Código a ejecutar si condicion2 es falsa
        }
    } else {
        // Código a ejecutar si condicion1 es falsa
    }
    ```

4. Ejemplos y práctica

    Revisar algunos de los ejercicios que se vienen trabajando, sobre la forma en que se están utilizando.

    Es importante comprender cómo funcionan las estructuras condicionales para controlar el flujo del programa.

    Recordar los conceptos clave del capítulo vistos sobre operadores lógicos.

[Ciclos en Javascript](./4-ciclos.md)
