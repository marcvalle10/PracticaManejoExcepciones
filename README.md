# PracticaManejoExcepciones: Son tres codigos diferentes que sirven para practicar manejo de exepciones.

--> En el primero el método auxiliar "caracterEn" toma una cadena y un entero como parámetros y realiza las siguientes acciones:

# Verifica si el entero está dentro del rango válido, es decir, entre 0 (inclusive) y la longitud de la cadena (exclusive).
# Si el entero está en el rango, devuelve el carácter en la posición correspondiente de la cadena utilizando el método "charAt".
# Si el entero está fuera del rango, lanza una excepción de tipo "Exception" con un mensaje indicando que la posición está fuera de rango.

--> En el segundo realiza las siguientes accines:
# Creación del objeto Scanner y lectura de entrada:
El código crea un objeto Scanner asociado a la entrada estándar (consola) y lee una línea de texto introducida por el usuario usando scanner.nextLine().
# Invocación del método caracterEn:
Luego, el código llama al método caracterEn definido en el ejercicio anterior, pasando la cadena de caracteres ingresada por el usuario (lectTeclado) y el entero 7 como argumentos. Esto corresponde a la acción de invocar el método con la cadena leída y mostrar el carácter en la posición 7.
# Captura de excepción:
El código envuelve la llamada al método caracterEn dentro de un bloque try-catch para capturar cualquier excepción que pueda surgir. Si se lanza una excepción debido a una posición fuera de rango, se muestra un mensaje de error como se requiere.

--> Por ultimo en el tercero hace lo siguiete:
# Definición de la clase NumeroNegativoExcepcion:
La clase NumeroNegativoExcepcion hereda de la clase base Exception y contiene dos constructores, uno sin parámetros y otro que recibe una cadena de mensaje como parámetro. Ambos constructores invocan los constructores correspondientes de la clase base Exception.

# Programa con método main para probar la excepción:
En el método main, se crea un objeto Scanner para leer la entrada del usuario. Luego, dentro de un bloque try-catch, se solicita al usuario ingresar un valor numérico. Si el valor es negativo, se lanza la excepción NumeroNegativoExcepcion con un mensaje personalizado. Si el valor es positivo, se calcula la raíz cuadrada y se imprime. También se captura la excepción InputMismatchException en caso de que el usuario ingrese algo que no sea un valor numérico.
