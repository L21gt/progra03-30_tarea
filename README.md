Luis Velasquez  
Carnet 24011341  
Curso JavaScript Testing  
3er semestre - Tarea 30_tarea  




# Debugging Review

Acabas de aprender tecnicas para ayudarte a superar cualquier situacion de depuracion.

Resumamos lo aprendido en un proceso de depuracion:

1. ¿Tu codigo genera errores? Si es asi, consulta el
   seguimiento de errores para conocer el tipo, la
   descripcion y la ubicacion del error. Accede a la
   ubicacion del error e intenta solucionarlo.

2.  ¿Tu codigo esta roto pero no genera errores?
    Revisalo usando declaraciones console.log().
    Cuando se produzcan resultados inesperados, aisla el
    error e intenta solucionarlo.

3. ¿Encontraste el error siguiendo los pasos 1 y 2, pero
   no puedes solucionarlo?
   Consulta la documentacion para asegurarte de usar
   correctamente todas las funciones de JavaScript.
   Si sigues sin poder solucionarlo, busca el problema
   en Google y consulta Stack Overflow para obtener ayuda.
   Tambien puedes utilizar inteligencia artificial, pero
   ten cuidado con el codigo que esta genere

Puede llevar algo de tiempo y practica, pero asi es como
todos los desarrolladores resuelven sus problemas, asi
que no te rindas y seras un experto en poco tiempo.


## Ejercicio:
En el editor de codigo, le proporcionamos una
implementacion fallida de una funcion llamada
isStringPerfectLength().
Esta funcion toma una cadena ( string), con una longitud
minima ( minLength) y una longitud maxima ( maxLength).
Debe devolver si el valor proporcionado string esta
dentro del rango de las dos longitudes.
Mas especificamente, si es mas largo que el valor
minLength y mas corto que el valor maxLength.

Hemos proporcionado tres casos de prueba de ejemplo al
final del archivo.
El primero comprueba si la cadena 'Dog' esta en el rango
de longitud de 2 y 4. En este caso, la funcion deberia
devolver la funcion true porque la longitud de la cadena
es 3, que se encuentra entre esos dos valores.
Los dos ejemplos siguientes fallan.
El primero falla porque la cadena es demasiado larga.
El segundo falla porque la cadena es demasiado corta.

Utilizando el proceso de depuracion que aprendio,
descrito anteriormente, busque y corrija todos los
errores en este codigo.

El codigo te mostrara errores desde el principio,
pero recuerda, ¡es algo bueno! Creemos que ya tienes
todas las habilidades para depurarlo.  

¡No te rindas y muestranos lo que has aprendido!
Sabemos que puedes lograrlo.

    //Descomenta el siguiente codigo para ver el error

    function isStringPerfectLength(string, minLength, maxLength {
        const stringLength = string.length;

        if (stringLenth > minLength) {
            return false;
        } else if (stringLenth < maxLength) {
            return false;
        } else {
            return true;
        }
    }

    // Should return true
    console.log("isStringPerfectLength('Dog', 2, 4) returns: " + isStringPerfectLength('Dog', 2, 4));

    // Should return false
    console.log("isStringPerfectLength('Mouse', 2, 4) returns: " + isStringPerfectLength('Mouse', 2, 4));

    // Should return false
    console.log("isStringPerfectLength('Cat', 4, 9) returns: " + isStringPerfectLength('Cat', 4, 9));