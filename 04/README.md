# Instrucciones de control de código en Python 🖥️🖱️

Aprenda temas de Python más avanzados mediante cuadernos interactivos.

### Objetivos de aprendizaje

En las unidades siguientes, se abordarán muchos temas intermedios sobre informática y los aplicaremos a ejemplos reales. Durante el proceso, obtendrá información sobre lo siguiente:

* Cómo escribir condicionales y cuándo usarlos
* Cómo escribir los bucles `while` y `for`, y cuándo usarlos
* Cómo crear sus propias funciones
* Cómo llamar a sus propias funciones
* Cómo usar parámetros y variables globales

<hr/>

## Introducción

En este módulo, obtendrá información sobre algunos conceptos intermedios del lenguaje de programación Python y practicará estos conceptos mediante ejemplos con temas de exploración espacial inspirados en la Administración Nacional de Aviación y Espacio (NASA).

<hr/>

## Ejercicio: [Comparación de valores de datos con código de Python](/2-conditions.ipynb)

En el mundo real, a veces solo realizamos una acción si se cumple una determinada condición. Esta es la idea detrás de los condicionales en la codificación. Por ejemplo, podemos querer lanzar un cohete solo si la temperatura está por encima de los 32 grados Fahrenheit.

Comencemos aprendiendo sobre las diferentes condiciones que podemos verificar para ayudarnos a decidir si realizar una acción o no.

### Condicionales

Las condiciones son cosas que deben cumplirse antes de cambiar las tareas. Podemos averiguar si se cumple una condición comparando dos valores. Para hacer esto, usamos algo llamado operadores lógicos. Los operadores lógicos devuelven `True`, si la declaración es verdadera, o `False`, si la declaración es falsa. Recuerde: los valores `True` y `False` se denominan booleanos.

Por ejemplo, si nuestra condición es comprobar si la temperatura está por encima del punto de congelación (para ver si se retrasaría el lanzamiento de un cohete), nuestra condición sería `temperatura > 32`. Esto nos daría `True` si la temperatura está por encima del punto de congelación y Falso si la temperatura está por debajo del punto de congelación.

Estos son algunos operadores lógicos comunes:

* Igual a: `x == y`
* Distinto que: `x != y`
* Menor que: `x < y`
* Menor o igual que: `x <= y`
* Mayor que: `x > y`
* Mayor o igual que: `x >= y`

<hr/>

## Ejercicio: [Control del flujo de código mediante instrucciones condicionales](/3-if-statements.ipynb)

Usamos declaraciones condicionales para decirle a la computadora qué hacer si alguna condición se cumple o no: haz esto; si no, haz otra cosa.

### Sentencia `If`

La sentencia condicional más básica es la sentencia `if`. La sentencia `if` comprueba si una condición es verdadera o no. Si la condición es verdadera, la sentencia `if` ejecuta el código que está definido dentro de la sentencia. Si la condición no es verdadera, se omite cualquier código que esté definido dentro de la instrucción `if`.

Algunos ejemplos del mundo real son:

* Si la temperatura está por encima del punto de congelación, el cohete se lanzará.
* Si los niveles de oxígeno bajan, tome un traje espacial y un tanque de oxígeno.

### Sentencia `Else`

La sentencia `else` amplía la sentencia condicional `if` y permite que los codificadores tengan más control sobre lo que sucede dependiendo del resultado de la condición. Una sentencia `else` debe escribirse después de una sentencia `if`. El programa siempre ejecuta el código que está definido dentro de la declaración `else` cuando no se cumple la condición en la declaración `if`.

### Sentencia `Else-if`

Python también admite verificaciones `else-if` (`elif`), para un mayor control de las acciones basadas en datos. La sentencia `elif` se escribe después de una sentencia `if` y antes de una sentencia `else`. Puede tener tantas sentencias `elif` como desee entre la sentencia `if` inicial y la sentencia `else` final.

La sentencia `elif` es simplemente otra sentencia `if`. Cuando no se cumplen las condiciones de la sentencia `if` inicial, el programa comprueba si se cumplen las condiciones de la siguiente sentencia `elif`. Cuando se cumplen las condiciones para la sentencia `elif`, se ejecuta el código que está definido dentro de la sentencia `elif`. Se omite cualquier código que esté definido en una instrucción `elif` o `else` subsiguiente.

<hr/>

## Ejercicio: [Repetición de código con los bucles while y for](/4-iterations.ipynb)

Las iteraciones, en la programación, permiten que los codificadores repitan un conjunto de instrucciones hasta que se cumpla una condición. Piensa en esto como si estuvieras atrapado en un bucle que continuará hasta que algo te diga que salgas.

### Bucle `While`

El bucle `while` es uno de los dos tipos de iteraciones que aprenderá. En este ciclo, primero debe especificar una condición y luego incluir el código sobre el que desea que se itere el ciclo. El ciclo primero verifica si la condición es `True` y si lo es, luego mira el código dentro del ciclo. Cuando la condición se vuelve `False`, el código en el ciclo se salta y el programa continúa ejecutando el resto de su código.

Si la condición en el bucle es `False` para empezar, el código dentro del bucle nunca se ejecuta. Durante un solo bucle, el programa pasa por el bucle y ejecuta el código. Una vez que el código está terminado, vuelve a mirar la condición para ver si todavía es `True`. Es necesario cambiar las variables en su bucle para tener eventualmente una condición que sea `False`, o de lo contrario se producirá un bucle infinito.

### Ciclo `For`

Los bucles `For` esencialmente realizan la misma tarea que los bucles `while`: tienden a centrarse en iterar un número determinado de veces. Los bucles `For` son geniales cuando quieres revisar una lista y ver cada uno de los elementos. En el siguiente código, hacemos una lista y luego revisamos todos los elementos y los imprimimos.

<hr/>

## Ejercicio: [Código de fragmento en funciones para facilitar la reusabilidad y la legibilidad](/5-functions.ipynb)

Podemos usar funciones para hacer que nuestro código sea más fácil de leer y de reutilizar. Por ejemplo, si escribiera un código para contar la cantidad de rocas de basalto, probablemente sería casi idéntico al código necesario para contar las rocas de las tierras altas. En lugar de hacer una declaración if para verificar el tipo de cada roca espacial, podemos escribir una función para las rocas espaciales y puede ejecutar el mismo código para verificar qué tipo de roca es cada vez.

`print()` es un ejemplo de una función en la que el código que muestra la salida en la pantalla es el mismo, y la única diferencia es lo que desea mostrar. En esta unidad, aprenderá a escribir su propia función.

<hr/>

## Ejercicio: [Importación de datos a partir de archivos de texto con Python](/6-read-text-file.ipynb)

En muchas aplicaciones de Python, deberá usar datos de una fuente externa, como:

* Un archivo de Excel con datos de seguimiento de las distintas partes de un cohete
* Un archivo de texto para leer las rocas que ve un vehículo lunar

En esta unidad, aprenderemos a leer y escribir datos de un archivo de texto usando las funciones integradas de Python.

<hr/>

## Ejercicio: [Uso de parámetros para especificar la variabilidad en las funciones](/7-parameters.ipynb)

Otro aspecto interesante de las funciones es que las variables creadas dentro de ellas solo existen dentro de la función.