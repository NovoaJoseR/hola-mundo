# hola_mundo
# primer programa en mi GitHub , bueno ni programa ni nada, que esto es un fichero de comentarios.

El fichero hola_mundo es el que escribe "hola mundo" en el terminal.
No escribo este ejemplo porque esté obsesionado con los '80; lo que te pasa es que te crees una bruja consumada, pero realmentea es que estás intoxicada, y eso que dicen que ya no tomas nada, pero me dicen por ahí, que sí, que sí,...

Una vez escrito este programa en un ordenador o en la web de GitHub, nos vamos a una máquina con Linux, y ahí abrimos un terminal, una vez ahí se ejecuta git clone con el path a este repositorio, en este caso es:

$ git hub https://github.com/NovoaJoseR/hola-mundo.git

Luego aparecerá el directorio debajo de donde estábamos, nos vamos ahí con el comando:

$ cd hola-mundo/

Vemos lo que tiene con ls y observamos que están este fichero de comantarios README.md más el del programa hola_mundo.c

Luego compilamos con gcc (que tenemos ya instalado desde hace tiempo en nuestro Linux), se compila así:

$ gcc -o hola hola_mundo.c 

Con eso el fichero de salida se llamará hola, y es el ejecutable, que para que saque el mensaje por el terminal tenemos que ejecutarlo así:

$ /hola

Y sale en la siguiente línea el mensaje.
Y eso es todo.
