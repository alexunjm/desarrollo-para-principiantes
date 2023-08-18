# Capítulo 2

## Funciones en JavaScript

En este capítulo, exploraremos el concepto de funciones en JavaScript, incluyendo cómo definir funciones, pasar argumentos, retornar valores y comprender el ámbito de las variables dentro de las funciones.

1. Definición de funciones

    Las funciones en JavaScript son bloques de código reutilizables que realizan una tarea específica.

    Se pueden definir funciones utilizando la palabra clave `function`, seguida del nombre de la función y los parámetros entre paréntesis.

    Ejemplo de definición de función:

    ```javascript
    function nombreDeLaFuncion(parametro1, parametro2) {
        // Código a ejecutar
    }
    ```

2. Pasar argumentos a funciones

    Los argumentos son valores que se pasan a una función cuando se llama.

    Las funciones pueden aceptar cero o más argumentos.

    Los argumentos se utilizan dentro de la función para realizar operaciones o tomar decisiones.

    Ejemplo de llamada a una función con argumentos:

    ```javascript
    nombreDeLaFuncion(valor1, valor2);
    ```

3. Retorno de valores en funciones

    Las funciones pueden devolver un valor utilizando la palabra clave return.

    El valor devuelto por la función se puede asignar a una variable o utilizar en otras operaciones.

    Ejemplo de retorno de valor en una función:

    ```javascript
    function nombreDeLaFuncion() {
        // Código a ejecutar
        return resultado;
    }
    ```

4. Ámbito de las variables en funciones

    Las variables declaradas dentro de una función tienen un ámbito local, lo que significa que solo están disponibles dentro de esa función.

    Las variables declaradas fuera de una función tienen un ámbito global y se pueden acceder desde cualquier parte del programa.

    Si se declara una variable con el mismo nombre tanto dentro como fuera de una función, la variable local tendrá prioridad dentro de la función.

    Ejemplo de ámbito de variables en funciones:

    ```javascript
    let variableGlobal = 10;

    function nombreDeLaFuncion() {
        let variableLocal = 5;
        console.log(variableLocal);  // Imprime 5
        console.log(variableGlobal); // Imprime 10
    }
    ```

5. Ejemplos y práctica

    Revisar todos los ejercicios que se vienen trabajando para crear funciones que definan el marco de la solución, darle un nombre adecuado y recibir los argumentos (o variables de entrada) como input del algoritmo y que haga return de la salida.

    Es importante comprender cómo funcionan los funciones para reutilizar algoritmos ya creados.

[Ejercicios](./6-ejercicios.md)

<!-- [Operadores en Javascript](./3-condicionales.md) -->
<!-- 

Una serie de ejercicios para practicar la estructura de un programa JavaScript, incluyendo variables, operadores, condicionales, ciclos y funciones.
Se pueden proporcionar ejemplos y soluciones para cada ejercicio.
Resumen del capítulo

Repaso de los conceptos clave del capítulo.
Enfatizar la importancia de comprender la estructura básica de un programa JavaScript.
Recursos adicionales

Sugerir recursos en línea, documentación y tutoriales para que los estudiantes profundicen en los conceptos presentados en el capítulo.
Este es solo un esquema general para el capítulo. Puedes expandir cada sección proporcionando ejemplos, explicaciones detalladas y ejercicios prácticos para que los estudiantes apliquen los conceptos aprendidos. Recuerda adaptar el contenido a tu público objetivo y el nivel de conocimiento que desees abordar. ¡Buena suerte con tu curso de programación en JavaScript!

//aunque no lo hemos visto a detalle aún, les adelanto

 -->
