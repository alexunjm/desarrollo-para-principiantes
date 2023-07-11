# Capítulo 2

## Ciclos

En este capítulo, exploraremos los diferentes tipos de ciclos en JavaScript, incluyendo el ciclo while, el ciclo do-while y el ciclo for. Estos ciclos permiten repetir bloques de código de manera eficiente y controlada.

1. Ciclo while

    El ciclo while ejecuta repetidamente un bloque de código mientras se cumple una condición especificada.

    La sintaxis básica del ciclo while es:

    ```javascript
    while (condicion) {
        // Código a repetir mientras se cumpla la condición
    }
    ```

    La condición se verifica antes de cada iteración. Si la condición es verdadera, el bloque de código se ejecuta; de lo contrario, el ciclo se detiene.

2. Ciclo do-while

    El ciclo do-while es similar al ciclo while, pero la condición se verifica después de ejecutar el bloque de código, lo que garantiza que el bloque se ejecute al menos una vez.

    La sintaxis básica del ciclo do-while es:

    ```javascript
    do {
        // Código a repetir al menos una vez
    } while (condicion);
    ```

    El bloque de código se ejecuta primero y luego la condición se verifica. Si la condición es verdadera, el ciclo se repite; de lo contrario, el ciclo se detiene.

3. Ciclo for

    El ciclo for permite ejecutar un bloque de código un número específico de veces.

    La sintaxis básica del ciclo for es:

    ```javascript
    for (inicialización; condicion; actualización) {
        // Código a repetir en cada iteración
    }
    ```

    La inicialización se ejecuta una vez antes de que comience el ciclo, la condición se verifica antes de cada iteración, y la actualización se realiza después de cada iteración.

    El ciclo for es especialmente útil cuando se conoce el número exacto de repeticiones

4. Ejemplos y práctica

    Revisar algunos de los ejercicios que se vienen trabajando, sobre la forma en que se están utilizando.

    Es importante comprender cómo funcionan los ciclos para automatizar tareas repetitivas y controlar el flujo del programa.

    Recordar los conceptos clave del capítulo vistos sobre ciclos.

    Veamos un ejemplo que nos ayude a comprender cuándo utilizar for o while

    ```javascript
    
    //ciclo for
    for(let i = 1; i <= 5; i++) {
        //esto se ejecuta 5 veces. Desde i = 1 hasta i = 5
    }

    //ciclo while
    let i = 1
    while(i <= 5) {
        //esto se ejecuta 5 veces. Desde i = 1 hasta i = 5
        i++
    }
    ```

[Funciones en Javascript](./5-funciones.md)
