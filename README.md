# Docker-DOOM

## - PASOS PREVIOS -

- Antes de empezar a usar 'Docker' necesitamos descargar el archivo necesario para poder ejecutar el `Doom`
- Teniendo en cuenta que el archivo subido originalmente ya no esta disponible, debemos buscar un mirror  de la página
- ´https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz´


## - INSTALACIÓN -

- Creamos 2 contenedores con el comando `for i in {1..2} ; do docker run -d -t ubuntu:14.04; done`

[img contenedores](https://github.com/DavidMuletMelia/Docker-DOOM/blob/main/doom/1.PNG)

[img contenedores](https://github.com/DavidMuletMelia/Docker-DOOM/blob/main/doom/2.PNG)

- Descomprimimos el archivo descargado anteriormente con el comando `tar xzvf dockerdoomd.tar.gz`

[img descompresion](https://github.com/DavidMuletMelia/Docker-DOOM/blob/main/doom/3.PNG)

- Por ultimo ejecutamos el archivo con el comando `./dockerdoomd`

## - VNC -

- Para conectarnos al juego necesitamos un cliente VNC, para ello he usado el programa 'Remmina'

[img remmina](https://github.com/DavidMuletMelia/Docker-DOOM/blob/main/doom/4.PNG)

- Nos conectamos por el puerto `5900` y con la contrasña `1234`


## - DOOM -

- Si todo ha ido bien, ya deberiamos ver y poder jugar a este clasico de Id Software

[img doom]()


