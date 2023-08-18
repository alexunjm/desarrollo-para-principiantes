Variables y Condicionales:

1. Escribe un programa que tome la edad de una persona como entrada y muestre un mensaje indicando si es mayor de edad o no.

```javascript
/*
1. Escribe un programa que tome la edad de una persona como entrada y muestre un mensaje indicando si es mayor de edad o no.
*/
function ejercicio1() {

    function validaMayoriaEdad(edad) {

        if (edad >= 18) {
            console.log('es mayor de edad en Colombia')
        } else {
            console.log('es menor de edad en Colombia')
        }
    }


    const edadIngresada = +prompt('ingrese edad')
    validaMayoriaEdad(edadIngresada)
}

ejercicio1()
```

2. Crea un programa que solicite dos números al usuario y muestre cuál de ellos es mayor.

```javascript


/*
2. Crea un programa que solicite dos números al usuario y muestre cuál de ellos es mayor.
*/
function ejercicio2() {

    function mayorEntreAyB(A, B) {

        let mayor = A

        if (B > mayor) {
            mayor = B
        }

        console.log('mayor es', mayor)
    }

    const A = +prompt('ingrese valor A')
    const B = +prompt('ingrese valor B')

    mayorEntreAyB(A, B)
}

ejercicio2()
```

3. Diseña un programa que determine si un número ingresado por el usuario es positivo, negativo o cero.

```javascript

/*
3. Diseña un programa que determine si un número ingresado por el usuario es positivo, negativo o cero
*/
function ejercicio3() {
    function tipoEntero(numero) {

        if (numero > 0) {
            console.log('el entero es positivo')
        } else if (numero < 0) {
            console.log('el entero es negativo')
        } else {
            console.log('el entero es cero')
        }
    }

    const numero = +prompt('ingrese un entero')
    tipoEntero(numero)
}

ejercicio3()
```

4. Desarrolla un programa que, dado un número, determine si es par o impar.

```javascript

/*
Desarrolla un programa que, dado un número, determine si es par o impar.
*/

function ejercicio4() {
    function parOimpar(num) {
        if (num % 2 == 0) {
            console.log('el numero es par')
        } else {
            console.log('el numero es impar')
        }
    }
    const numero = +prompt('ingrese un numero')
    parOimpar(numero)
}

ejercicio4()
```

5. Escribe un programa que solicite el nombre de un día de la semana y muestre si es laborable o de descanso.

```javascript

/*
5. Escribe un programa que solicite el nombre de un día de la semana y muestre si es laborable o de descanso.
*/
function ejercicio5() {
    function validarDiaLaborable(dia) {
        const descanso = 'domingo'
        if (dia == descanso) {
            console.log('el dia es no laborable')
        } else {
            console.log('el dia es laborable')
        }
    }
    const dia = prompt('ingrese el dia').toLowerCase()
    validarDiaLaborable(dia)
}

ejercicio5()
```

Ciclos y Arreglos:

6. Crea un programa que muestre los primeros N números naturales.
7. Diseña un programa que sume todos los números pares del 1 al N.
8. Escribe un programa que calcule el factorial de un número dado por el usuario.
9.  Desarrolla un programa que genere la serie de Fibonacci hasta el término N.
10. Crea un programa que encuentre el número mayor en un arreglo de números enteros.
11. Diseña un programa que cuente la cantidad de números negativos en un arreglo.
12. Escribe un programa que determine si un elemento dado está presente en un arreglo.
13. Desarrolla un programa que muestre los elementos únicos de un arreglo (sin duplicados).

Ciclos Anidados:

14. Crea un programa que genere el patrón de asteriscos en forma de triángulo invertido.
15. Diseña un programa que imprima la tabla de multiplicar del 1 al 10.
16. Escribe un programa que genere un patrón numérico de escalera.
17. Desarrolla un programa que muestre un patrón de asteriscos en forma de pirámide.
18. Crea un programa que calcule la suma de matrices cuadradas.
19. Diseña un programa que muestre una matriz transpuesta.
20. Escribe un programa que encuentre la intersección de dos arreglos (elementos comunes).

Estos enunciados deberían proporcionarte una variedad de ejercicios para practicar y mejorar tus habilidades de programación. ¡Diviértete resolviéndolos! Si necesitas ayuda con algún código en particular, no dudes en preguntar.
