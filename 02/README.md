# Instalación de herramientas de codificación para el desarrollo de Python 👨‍💻⚙️

Obtenga información sobre qué es la codificación e instale herramientas que la faciliten.

### Objetivos de aprendizaje

En este módulo, obtendrá información y probará software que ayuda a los desarrolladores, especialmente en la exploración de datos. Durante el proceso, aprenderá lo siguiente:

* Qué es un lenguaje de programación
* El procedimiento para instalar Visual Studio Code y las ventajas de este editor de código
* El procedimiento para instalar extensiones a fin de mejorar la experiencia de Visual Studio Code
* Instalación de Python y por qué es un lenguaje de programación tan popular
* El procedimiento para ejecutar una instancia básica de Jupyter Notebook en Visual Studio Code

### Requisitos previos

* Un equipo con Windows, Mac o Linux
* Conocimientos sobre cómo descargar programas de Internet

<hr/>

## Introducción

En este módulo, se presentarán Visual Studio Code, Python y Jupyter Notebook. Aprenderemos a instalar todo el software y los paquetes que necesitaremos para empezar a escribir código y explorar distintos tipos de datos, en función de la ruta de acceso de Learning en la que estemos trabajando.

<hr/>

## Definición de un lenguaje de programación

En la unidad anterior, hemos hablado de que aprender a programar es una gran aptitud. Pero ¿qué es la codificación?

### ¿Qué es el código?

Las líneas de código son instrucciones que los humanos proporcionan a los equipos para hacer cosas. Aunque pueda escuchar que los equipos son inteligentes y asombrosos, por sí mismos solo son buenos en algo: en cumplir instrucciones explícitas.

El código permite indicar a los vehículos lunares por dónde moverse y a los cohetes cómo volar. Sin el código, los equipos no serían más que un montón de metal. Pero con el código, los equipos pueden realizar acciones fuera del alcance de los humanos.

### ¿Cómo se programa?

Para programar, o escribir instrucciones para los equipos, es necesario escribir en un lenguaje que entiendan. Esta comunicación adopta la forma de lenguajes de programación. El código que está escrito en estos lenguajes se traduce en unos y ceros, lo que se denomina código binario, que los equipos pueden leer y ejecutar como acciones. Hay muchos lenguajes de programación en todo el mundo, y cada uno se especializa en algo diferente. En esta ruta de aprendizaje nos centraremos en Python, un lenguaje que funciona bien para solucionar problemas de datos de gran tamaño.

### Ejecución y depuración de código

Una vez que un desarrollador ha escrito código, lo ejecuta. Al ejecutar el código, se indica al equipo que lo lea y lleve a cabo las instrucciones. Cuando se le indica al equipo que ejecute el código, realizará una de estas dos acciones: ejecutarlo correctamente o indicar que se ha producido un error en algún lugar.

Los errores en el código se conocen como "errores" y su corrección se denomina "depuración". La depuración es una parte importante de la programación y una gran aptitud que se puede aplicar a otros muchos aspectos de la vida.

Básicamente, la depuración consiste en seguir el método científico. Un desarrollador:

* Tendrá una hipótesis de lo que debería haber sucedido
* Para recopilar información, examinará el código con una herramienta denominada depurador, o bien lo leerá manualmente
* Analizará en qué difiere la ejecución del comportamiento esperado
* Modificará el código
* Volverá a probarlo

<hr/>

## Capacidad de solucionar problemas con Visual Studio Code

Ahora que ha visto una breve introducción al código, puede pasar a aprender las herramientas que usan los desarrolladores para facilitar la codificación. En concreto, en esta unidad, obtendrá información sobre los editores de código y Visual Studio Code.

### ¿Qué es Visual Studio Code?

[Visual Studio Code](https://code.visualstudio.com/) (a menudo conocido como VS Code) es un editor de código gratuito, de código abierto y extensible. Esta descripción se puede desglosar para entenderla mejor:

* **Editor de código**: un editor de código se crea específicamente para escribir, ejecutar y depurar código. Los editores de código se pueden comparar con una aplicación como Microsoft Word, pero incluyen funcionalidades adicionales, como autocompletar las funciones de código y la capacidad de ejecutar código.

* **De código abierto**: el software de código abierto (OSS) tiene su código disponible para que cualquiera lo pueda explorar, modificar y mejorar. La principal conclusión de esto es que cualquier usuario puede crear una característica en software como Visual Studio Code y contribuir al código fuente para que otros usuarios la puedan utilizar. Puede encontrar el [proyecto Visual Studio de código abierto en GitHub](https://github.com/microsoft/vscode).

* **Extensible**: significa que algo se puede ampliar y expandir. En el contexto de Visual Studio Code, ser extensible significa que puede descargar extensiones, o incluso crearlas, para ajustar Visual Studio Code de forma exacta a un estilo de trabajo. Piense en los mods de un juego o las personalizaciones. Si la combinación de colores le afecta a la vista o no se admite un lenguaje de programación complejo, puede personalizar Visual Studio Code para agregar colores nuevos o la compatibilidad con ese lenguaje. Puede encontrar las [extensiones de Visual Studio Code en marketplace](https://marketplace.visualstudio.com/) o descubrir cómo [crear una extensión propia en la documentación de Visual Studio Code](https://code.visualstudio.com/api).

### Por qué Visual Studio Code es popular entre la comunidad de desarrolladores

Se suele suponer que la popularidad de Visual Studio Code se debe a que es gratuito. Es una razón importante, pero otros muchos editores también lo son. Visual Studio Code es de código abierto y tiene una nutrida comunidad de desarrolladores que trabajan para incorporar nuevas características. Actualmente, en Visual Studio Code se admiten casi todos los lenguajes de programación principales. Además, para cada lenguaje, marco o estilo de trabajo, es probable que haya una extensión con el objetivo de que los desarrolladores puedan tener una mejor experiencia. Muchos lo han elogiado también por su facilidad de configuración y puesta en marcha en todas las plataformas.

<hr/>

## Descripción de la importancia de Python en la solución de problemas de macrodatos

[Python](https://www.python.org/) es el lenguaje de programación que va a usar en esta ruta de aprendizaje. Aunque pueda parecer que va a obtener información sobre un único lenguaje de programación, los conceptos que se describen se pueden aplicar a muchos otros.

### Orígenes de Python

En 1991, Guido van Rossum creó Python y lo bautizó así por el programa de televisión de los Monty Python. Python es un lenguaje de programación general por lo que, desde el punto de vista del programador, el código se asemeja más a un idioma natural (en inglés) y, por tanto, es más fácil de leer y escribir. Python realiza el trabajo pesado en segundo plano y convierte instrucciones de lenguaje relativamente naturales en comandos que un equipo puede ejecutar.

### ¿Por qué Python?

Es posible que se pregunte por qué de todos los lenguajes de programación existentes se ha elegido Python. Durante los últimos 15 años, Python ha crecido en popularidad y a menudo se considera un excelente lenguaje de programación para principiantes. También es versátil y se puede aplicar a temas informáticos avanzados, como la ciencia de datos y el aprendizaje automático. Además, Python tiene muchos paquetes y bibliotecas de código escritos por otros usuarios. Puede incluirlos en sus propios proyectos para disminuir el código que debe escribir.

### Ejemplos del mundo real de Python en funcionamiento

Ejemplos de software que incluyen código de Python son YouTube, Dropbox y Google. [Incluso la NASA tiene una página de proyectos de código abierto](https://code.nasa.gov/), muchos de ellos programados en Python.

### Jupyter Notebook y Python

Se usará un tipo de archivo denominado [Jupyter Notebook](https://jupyter.org/) para ayudarle a aprender Python. Jupyter Notebook admite Python en un estilo REPL (read-eval-print loop), lo que significa que los usuarios pueden escribir unas cuantas líneas de código en un archivo, ejecutarlas dentro del archivo y, después, escribir más código y continuar la ejecución. Los cuadernos de Jupyter Notebook también admiten la reejecución de "celdas", que son fragmentos de código. Este tipo de entorno de codificación crea una gran experiencia para aprender un nuevo lenguaje de programación. Pero no se preocupe, la instalación de la extensión de Python para Visual Studio Code instala el cuaderno automáticamente.

## Ejercicio: Instalación y configuración de Visual Studio Code para la exploración de datos

Aunque leer sobre estas tecnologías ha sido excelente, una manera mucho más interesante de conocerlas es instalarlas y comenzar a usarlas. En esta unidad se describe cómo instalar Visual Studio Code.

Si está realizando este módulo como parte de una ruta de aprendizaje, probablemente tenga la oportunidad de escribir todo el código en una experiencia de cuaderno integrada en el explorador desde el módulo de Microsoft Learn mismo, con lo cual no tendrá que instalar estas herramientas de desarrollador para completar el módulo. Sin embargo, configurar estas herramientas es una buena forma de empezar su itinerario personal como desarrollador, así que lo recomendamos igualmente.

### Instalación de Visual Studio Code

Como se ha mencionado antes, Visual Studio Code es gratuito. Si usa un equipo Windows, puede [descargarlo en la página de aprendizaje de Visual Studio Code](https://code.visualstudio.com/Download). Descargue el paquete de codificación para Python, que también instalará Python y las extensiones necesarias. Cuando el programa haya terminado de descargarse, ejecute el archivo ejecutable para iniciar el proceso de instalación.

Después de iniciar la instalación, se le pedirá que acepte el contrato de licencia y rellene las preferencias de la aplicación. También se le preguntará dónde instalar el programa. Lea y acepte el contrato de licencia y, luego, seleccione **Siguiente**.

![vs-code-license](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/vs-code-license.png)

![vs-code-preferences](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/vs-code-preferences.png)

Por último, seleccione **Instalar** en la última ventana para finalizar la instalación.

### Configuración de Visual Studio Code

Una vez que haya instalado Visual Studio Code, tiene la posibilidad de abrirlo por sí solo. Si no puede ver el cuadro de diálogo de inicio, simplemente busque la aplicación en el equipo e iníciela.

La primera vez que entre en Visual Studio Code, verá una ventana de **Introducción**. Para empezar, cerremos esta ventana. En el lado izquierdo de la pantalla verá que hay varios iconos que, al seleccionarlos, abren otras características de Visual Studio Code. A continuación, se muestra una breve descripción de algunas de las secciones que se van a usar.

![vs-code-welcome-screen](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/vs-code-welcome-screen.png)

* **Explorador**: muestra los archivos que se han abierto y el contenido de la carpeta, si se encuentra en una.
* **Buscar**: permite buscar una palabra concreta o una colección de palabras en el archivo.
* **Control de código fuente**: ayuda a escribir o compartir código con otros usuarios.
* **Ejecutar y depurar**: Ejecuta y depura el código que escribe
* **Extensiones**: muestra todas las adiciones realizadas por usuarios de todo el mundo. Hay diferentes temas de color, lenguajes de programación, etc. Puede instalar y personalizar Visual Studio Code como prefiera

<hr/>

## Ejercicio: Instalación de Python para usarlo en Visual Studio Code para la exploración de datos

Ahora que instaló Visual Studio Code, tendrá que descargar Python para que el equipo sepa cómo ejecutar e interpretar el código que escriba.

Para empezar, instale [Python 3.10 (o versiones posteriores) de python.org](https://www.python.org/downloads/). Seleccione **Descargar Python X.XX** para empezar la instalación. Una vez que descarga el archivo ejecutable, debe ejecutarlo para realizar la instalación. Estas instrucciones son para un equipo Windows; si tiene Linux o Mac, use los vínculos correspondientes del sistema operativo.

Cuando haya terminado, se lo dirigirá a una ventana de configuración en la que deberá seguir los pasos de instalación siguientes:

1. Active la casilla para **Agregar Python X.XX a PATH** y, luego, seleccione **Instalar ahora**.

    ![python-preferences](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/python-preferences.png)

2. Espere a que el programa termine de instalarse y, después, seleccione **Cerrar**.

    ![python-finish-install](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/python-finish-install.png)

Python ya está instalado. En la unidad siguiente obtendrá información sobre cómo ejecutar un programa de Python en Visual Studio Code.

<hr/>

## Ejercicio: Instalación de las extensiones de Visual Studio Code necesarias para la exploración de datos

En esta unidad, obtendrá información sobre la pestaña Extensiones de Visual Studio Code y cómo instalar la extensión Python e IntelliCode.

### Instalación de la extensión de Python

Seleccione la pestaña de extensión de Visual Studio Code para acceder a todas las herramientas de código abierto de Python que serán útiles en esta ruta de aprendizaje. En la pestaña Extensión se ven tres bloques en forma de "L" y otro bloque flotante en la derecha.

Si quiere, puede explorar el marketplace de extensiones e instalar las que le gustaría tener, pero para este tutorial, se instalará la de Python.

1. Cuando esté en el marketplace de extensiones, vaya a la barra de búsqueda y escriba "Python".
2. Busque la extensión denominada solo Python y publicada por Microsoft; debe ser el primer resultado.
3. Seleccione la extensión y, luego, seleccione **Instalar**.

![install-extension-python](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/install-python.png)

Después de instalar la extensión de Python, debe cerrar Visual Studio Code y volver a abrirlo para asegurarse de que se reconoce.

La extensión de Python le permite crear archivos de Python y Jupyter Notebook que pueden hacer lo siguiente:

* Ayudarlo a escribir correctamente código con formato
* Corregir errores tipográficos
* Ejecutar el código que escribe

### Instalación de la extensión IntelliCode

Mientras todavía está en la pestaña de extensiones, vuelva a la barra de búsqueda y escriba "intellicode". A continuación, selecciónelo en la lista (debería ser el primer resultado). Seleccione **Instalar**.

IntelliCode recomienda código cuando se escriben programas. Es una herramienta ideal para principiantes que quizás no sepa cuál es la sintaxis exacta.

![install-intellicode](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/install-intellicode.png)

<hr/>

## Ejercicio: Creación de un archivo de Jupyter Notebook en Visual Studio Code y ejecución de un programa sencillo

Ahora que ha instalado todo lo que necesita, puede crear un archivo de Jupyter Notebook y comenzar la codificación.

### Creación de un archivo Jupyter Notebook

Para empezar, cree una carpeta para organizar fácilmente todos los archivos de Jupyter que va a crear. Elija una ubicación de fácil acceso en el equipo, como la carpeta de documentos o el escritorio, y cree una carpeta con un nombre similar a `Jupyter files` o `Python`.

Cree un archivo de Jupyter Notebook que ejecutará el código de Python:

1. Abra Visual Studio Code.
2. Seleccione **Archivo**>**Nuevo archivo** (o presione `Ctrl-N`). Se abre un archivo en blanco.
3. Guárdelo como archivo de Jupyter:
    - Seleccione **Archivo**>**Guardar** (o escriba `Ctrl-S`).
    - Asigne al archivo el nombre que prefiera.
    - Seleccione la ubicación **Guardar como** en la carpeta que acaba de crear.
    - Cambie el tipo de archivo a "Jupyter" en el menú desplegable. También puede agregar la extensión de archivo `.ipynb`, que cambia el tipo de archivo a "Jupyter" de manera automática.

Sabrá que ha funcionado si ve el nombre de archivo seguido de ".ipynb" en la parte superior izquierda de la pantalla y el archivo muestra celdas en lugar de la vista sólida del editor cuando se abre en Visual Studio Code.

### Configuración del entorno de Python

Cuando tiene un archivo de Jupyter Notebook, debe elegir el entorno de Python que va a usar. Es posible que Visual Studio Code haya reconocido a Python una vez que lo instala. Pero si no es así, elija **Select Kernel** (Seleccionar kernel) en la esquina superior derecha de la pantalla y, después, seleccione el entorno de Python.

![select-python-kernel](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/select-python-kernel.png)

Ahora en VS Code se muestra la versión de Python seleccionada.

![jupyter-environment](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/jupyter-environment.png)

A continuación, tendrá que agregar cuadernos de Jupyter Notebook a la ruta de acceso.

1. Escriba "2+2" en la primera línea del editor.
2. Seleccione el botón de reproducción situado a la izquierda de la celda. Aparece una ventana en la que se le pide que instale cuadernos de Jupyter Notebook.
3. Seleccione **Instalar** para iniciar la instalación. La instalación puede tardar hasta cinco minutos, por lo que es posible que tenga que esperar.

![install-jupyter](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/install-jupyter.png)

Ahora se debería instalar Jupyter Notebook en el equipo. Antes de continuar, asegúrese de que el kernel de Jupyter Notebook también se ejecuta con la versión correcta de Python. Puede ver la versión en la esquina superior derecha de Visual Studio Code. Asegúrese de que, al volver a seleccionar el botón de reproducción, el programa imprime "4".

### Información sobre Jupyter Notebook

En [Jupyter Notebook para Visual Studio Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) se incluye documentación de calidad sobre cómo usar el entorno. En los cuadernos de Jupyter Notebook, el código se escribe en celdas.

* Seleccione un botón Más en la parte superior del archivo para crear una celda debajo de la actual. Puede crear una celda de **Código** o una de **Markdown**.
* Seleccione la papelera que hay encima de una celda para eliminarla.
* Arrastre la celda desde el lado izquierdo para subir o bajar la celda respecto de las celdas que la rodean.
* Use el botón de reproducción a la izquierda de cada celda para ejecutarla.

Después de ejecutar una celda, aparecerá un número entre corchetes. Con este número podrá hacer un seguimiento de las células que ejecuta. Esto es importante porque, como recordará, puede volver a ejecutar las celdas de un cuaderno de Jupyter Notebook, lo que podría cambiar las variables o el estado del programa.

Si observa la parte superior del archivo, verá que puede seleccionar Ejecutar todo para ejecutar todas las celdas del cuaderno a la vez. Por último, puede seleccionar el botón Interrumpir de color rojo para forzar la detención del programa en cualquier momento.

### Escritura y ejecución de un programa sencillo

Ahora probará la configuración mediante la escritura de un sencillo programa "Hola mundo". En la primera celda, escriba el código siguiente y, después, seleccione el botón de reproducción.

```python
"Hello World"
```

![run-jupyter](https://learn.microsoft.com/es-es/training/modules/install-code-tools-python-nasa/media/run-jupyter.png)

Debajo de la celda que ejecutó, debería haber una salida en la que se muestra **Hola mundo**.