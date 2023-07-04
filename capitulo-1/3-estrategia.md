# Capítulo 1

## Estrategia

### Análisis del problema

Es importante responder algunas preguntas

- ¿Cuál es el objetivo de la solución?

    `Imprimir el conteo regresivo desde un número n dado`

- ¿Cuáles son los datos de entrada?

    `Número n desde el cual iniciará el conteo regresivo`

- ¿Se debe realizar algún tipo de cálculo o proceso antes de mostrar el resultado final?

    `El número n deberá ir disminuyendo de a 1 en 1`

- ¿De qué forma (formato) debemos presentar nuestros datos al tener el resultado?

    `Imprimir cada número, uno debajo del otro`

### Diseño de la solución

Utilizando los datos del paso anterior, se procede a realizar un diseño que trate de solucionar el problema y se escribe el paso a paso; o bien, se realiza el diagrama de flujo que representa el paso a paso de la solución

![Image](./img/conteo-regresivo.svg "Diagrama de flujo")

### Validación de la solución

Apopyarse de una prueba de escritorio, para verificar que el diseño realizado cumple con las especificaciones del problema que se quiere solucionar.

Para dicha prueba, se recomienda crear una tabla (escrita a mano o en una hoja de cálculo) con las siguientes características

- Variables de entrada
- Variables internas del proceso
- (**opcional**) cálculos u operaciones lógicas; ecuaciones, condicionales, ...
- Variables de salida
- En lo posible, utilizar cada línea de la tabla con los valores calculados o guardados en dichas variables

Teniendo las características mencionadas, basta con revisar si la salida es lo que se espera.

| n  | n > 0  | salida |
|----|--------|--------|
| 5  |        |        |
|    |        | 5      |
|    | 5 > 0  |        |
| 4  |        |        |
|    |        | 4      |
|    | 4 > 0  |        |
| 3  |        |        |
|    |        | 3      |
|    | 3 > 0  |        |
| 2  |        |        |
|    |        | 2      |
|    | 2 > 0  |        |
| 1  |        |        |
|    |        | 1      |
|    | 1 > 0  |        |

### Implementación

Llevar el diseño del algoritmo al lenguaje de programación de preferencia (o preestablecido)

```javascript
function conteoRegresivo() {
  let n = +prompt('Conteo regresivo desde');

  while (n > 0) {
    console.log(n);
    n = n - 1
  }

}

conteoRegresivo()
```

[Ejercicios](./2-ejercicios.md)
[Estrategia de trabajo](./3-estrategia.md)
