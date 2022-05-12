# DockerMac

## Objetivo

Ejecutar varios contenedores en Docker para comprobar la correcta instalación y funcionamiento.

## Comprobación de la instalación

Para comprobar la correcta instalación de docker ejecutaremos el siguiente comando en nuestra terminal de mac que nos devolverá la información relacionada con la instalación de Docker.
~~~
docker info
~~~
![dockerinfo](https://github.com/cosmetorandellborras/DockerMac/blob/main/dockerinfo.png)

## Ejecución de contenedores

Procederemos a ejecutar diferentes contenedores para comprobar el correcto funcionamiento de Docker.

### Contenedor hello-world

Para ejecutar este contenedor ejecutaremos el siguiente comando en nuestra terminal de mac, este nos hará un pull del contenedor y lo ejecutará.
~~~
docker run hello-world
~~~
![dockerHelloWorld](https://github.com/cosmetorandellborras/DockerMac/blob/main/docker%20hello-world.png)

### Contenedor Docker WhaleSay

Para ejecutar este contenedor ejecutaremos el siguiente comando en nuestra terminal de mac, este nos hará un pull del contenedor y lo ejecutará. 
~~~
docker run docker/whalesay cowsay Hello World
~~~

![dockerWhale](https://github.com/cosmetorandellborras/DockerMac/blob/main/docker%20whale.png)

### Contenedor danielkraic/asciiquarium

Para ejecutar este contenedor ejecutaremos el siguiente comando en nuestra terminal de mac, este nos hará un pull del contenedor y lo ejecutará. 
~~~
docker run -it --rm danielkraic/asciiquarium
~~~
![DockerAsciiquarium](https://github.com/cosmetorandellborras/DockerMac/blob/main/docker%20asciiquarium.png)
