# Docker-DOOM

## - PASOS PREVIOS -

- Antes de empezar a usar 'Docker' necesitamos descargar el archivo necesario para poder ejecutar el `Doom`
- Teniendo en cuenta que el archivo subido originalmente ya no esta disponible, debemos buscar un [mirror (https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz) de la página



## - INSTALACIÓN -

- Ejecutamos el `.exe` y le damos a 'siguiente' hasta que termine

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/1.PNG)

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/2.PNG)

- Una vez finalizado, le damos a 'Close'

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/3.PNG)

- Leemos y aceptamos los terminos y condiciones y continuamos

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/4.PNG)

- Ahora, una parte importante a tener en cuenta es que necesitamos tener instalado el 'WSL 2' en nuestro equipo, en caso de no tenerlo nos aparecera el siguente mensaje

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/5.PNG)

- Para instalarlo simplemente vamos al link que nos proporciona el mensaje `https://aka.ms/wsl2kernel.` y nos llevara a la la pagina de 'Microsoft' donde podemos descargar el 'WSL 2' en el siguente link

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/6.PNG)

- Nos dejara el siguente `.exe`

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/7.PNG)

- Ejecutamos normalmente y seguimos los pasos que nos indica el instalador

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/8.PNG)

- Una vez instalado, le damos a `Restart` en el mensaje que nos salió al abrir 'Docker'

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/5.PNG)

- Y ya tendriamos la instalación lista

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/9.PNG)

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/10.PNG)


## - CREACIÓN DEL 'HELLO WORLD' -

- Para crear el 'Hello World' abrimos el 'PowerShell' y ejecutamos el comando `docker run hello-world`

- Nos dirá que no puede encontrar la imagen de 'Hello World' localmente, con lo cual la descargará

- Una vez descargada, la ejecutará automaticamente y podremos comprobar que tenemos 'Docker' listo para funcionar

![Image text](https://github.com/DavidMuletMelia/Instalacion-de-Docker-en-Windows-Linux-o-Mac/blob/main/docker/11.PNG)
