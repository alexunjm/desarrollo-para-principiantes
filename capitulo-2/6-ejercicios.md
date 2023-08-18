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

//ejercicio1()


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

//ejercicio2()

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

//ejercicio3()

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

//ejercicio4()

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
