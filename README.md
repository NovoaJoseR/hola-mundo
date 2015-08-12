# hola_mundo
primer programa en mi GitHub , bueno realmente esto es un fichero de comentarios, el programa está en el otro fichero "hola_mundo.c"

El fichero hola_mundo es el que escribe "hola mundo" en el terminal.

Una vez escrito este programa en un ordenador o en la web de GitHub, nos vamos a una máquina con Linux, y ahí abrimos un terminal, una vez ahí se ejecuta git clone con el path a este repositorio, en este caso es:

$ git clone https://github.com/NovoaJoseR/hola-mundo.git

Luego aparecerá el directorio debajo de donde estábamos, nos vamos ahí con el comando:

$ cd hola-mundo/

Vemos lo que tiene con ls y observamos que están este fichero de comantarios README.md más el del programa hola_mundo.c

Luego compilamos con gcc (que tenemos ya instalado desde hace tiempo en nuestro Linux), se compila así:

$ gcc -o hola hola_mundo.c 

Con eso el fichero de salida se llamará hola, y es el ejecutable, que para que saque el mensaje por el terminal tenemos que ejecutarlo así:

$ ./hola

Y sale en la siguiente línea el mensaje.
Y eso es todo.

También lo pruebo en MAC y funciona igual, además como me he instalado el GitHub desktop para MAC, lo puedo llevar directamente, pero de momento prefiero hacerlo con la línea de comandos a partir de una ventana de terminal ya que me parece un tanto extraño el desktop.
