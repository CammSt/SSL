<h1>🖥️ TP0 de Sintaxis y Semántica de los Lenguajes 🖥️</h1>

1. 📋 **Objetivos:**
  - Demostrar capacidad para editar, compilar, y ejecutar programas C mediant el desarrollo de un programa simple.
  - Tener un primer contacto con las herramientas necesarias para abordar la resolución de los trabajos posteriores.

2. 📋 **¿En qué consiste este trabajo?**

   Durante el armado del entorno de desarrollo se eligió e instaló el compilador C11.
   
   El proyecto consiste en un simple archivo hello.c en el que la función main se encarga de mostrar por consola el conocido mensaje de 'Hello World'.

   Para poner en funcionamiento el proyecto se deben seguir los siguientes pasos:

   - gcc hello.c -std=c11 -o hello.exe
       - 'gcc': Invoca al compilador GNU C Compiler (GCC)
       - 'hello.c': Especifica el nombre del archivo fuente que se va a compilar, en este caso, hello.c.
       - '-std=c11': Establece el estándar de lenguaje al que se compilará el código fuente. En este caso, se utiliza -std=c11 para indicar que el código debe compilarse conforme al estándar C11.
       - '-o hello.exe': Especifica el nombre del archivo de salida generado después de la compilación. En este caso, se utiliza -o para indicar el nombre del archivo ejecutable de salida, que será hello.exe.
         
   - ./hello > output.txt
       - './hello': Ejecuta el programa compilado hello, que se encuentra en el directorio actual (./ indica la ubicación actual).
       - '>': Redirecciona la salida estándar del programa (stdout) hacia un archivo. En este caso, se utiliza output.txt como nombre del archivo de salida.
       - 'output.txt': Especifica el nombre del archivo donde se redireccionará la salida estándar del programa.
