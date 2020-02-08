# Ejemplos HTML5 de Línea de Código
http://lineadecodigo.com/categoria/html5/

## Ejecutarlo 
Puedes abrir cada uno de los ficheros directamente en el navegador.
Pero hemos adjuntado un servidor web mediante un dockerfile ya que algunos ficheros requieren estar ejecutándose en un servidor.
Para poder ejecutarlo debes de escribir los siguiente:

~~~html
$ docker build -t my-apache2 .
$ docker run -dit --name my-running-app -p 8080:80 my-apache2
~~