# comandos-linux
Este es un repositorio de comandos de Linux del curso de Sistemas Operativos

| Comandos                                                                      | Funciones     |
| --- | --- |
|sudo reboot                                                                    | reinicia la máquina 
|history                                                                        | comandos ya digitados 
|cd                                                                             | cambie de directorio 
|ls                                                                             | listar archivos de una carpeta 
|chmod                                                                          | cambiar permisos a un archivo 
|chown                                                                          | cambiar el usuario a ser propietario
|df-h                                                                           | espacio en disco usado 
|mount                                                                          | montaje de dispositivos en el sistema de archivos 
|Gparted                                                                        | administrar las particiones 
|kill-9 $PID                                                                    | matar un proceso
|ps -aux                                                                        | mostrar los procesos 
|pwd                                                                            | mostrar el directorio actual 
|chmod +x <file name>                                                           | cambiar los permisos de un archivo .sh 
|chmod 755 <file name>                                                          | cambiar los permisos de un archivo .sh 
|cat                                                                            | ver el contenido del archivo 
|docker attach (nombre del contenedor)                                          | entrar al contenedor 
|docker images                                                                  | ver imágenes del docker 
|docker pull nginx                                                              | abrir el repositorio 
|docker ps -a                                                                   | ver los archivos 
|docker history nginx                                                           | ver el historial del repositorio 
|docker info                                                                    | comprobar el driver que se está utilizando
|uname -a                                                                       | ver si uno puede ejecutar el “overlay” 
|sudo apt-get install -t jessie-backports linux-image-amd64                     | instalar “kernel” 4.9
|docker network ls                                                              | ver las redes virtuales
|sudo ifconfig docker0                                                          | crear docker 
|docker network create —driver bridge red1                                      | crear redes para diferentes contenedores 
|docker pull ubuntu                                                             | descargar imagen
|docker run ubuntu                                                              | ejecutar algo con una de estas imágenes en un contenedor 
|docker ps -a                                                                   | ver los que están en ejecución y los que no
|docker run -ti ubuntu                                                          | llamada interactiva
|docker run -ti —rm ubuntu                                                      | borrar contenedor del disco
|apt                                                                            | instala desde el repertorio de Ubuntu
|sudo apt update && sudo apt upgrade                                            | actualizar el sistema
|pwd                                                                            | muestra la ruta
|/                                                                              | están todas las carpetas del sistema operativo
|cd ..                                                                          | ir hacia atrás en las carpetas
|nano ([name].txt)                                                              | abre un archivo de texto, puede agregarle nombre previo o después a la hora de  guardarlo
|mkdir [name]                                                                   | crear una carpeta nueva
|rm [name] / rm [name] -R                                                       | remueve archivos o carpetas, +f al final es forzado
|clear                                                                          | vacia la terminal
|htop o top                                                                     | muestra los procesos corriendo en vivo 
|ps -aux                                                                        | imprime los procesos de ese momento
|man apt                                                                        | como usar apt
|sudo su                                                                        | volverse super administrador
|whoami                                                                         | mostrar el usuario que somos
|exit                                                                           | para volver al usuario inicial, cierra la terminal, salirnos de donde estábamos
|more [name].txt                                                                | imprime el contenido del archivo, para archivos que son muy largos
|tail -n 5 [name].txt                                                           | ver el final del archivo según cantidad de líneas
|head -n 5 [name].txt                                                           | ver el principio del archivo según cantidad de líneas
|cp [name].txt [new name]                                                       | copiar archivo
|mv [name].txt [carpeta]/                                                       | mover un archivo
|sudo adduser [new username]                                                    | crear un nuevo usuario
|sudo passwd [username]                                                         | cambiar de contraseña
|cntrl + c                                                                      | detener un proceso 
|history  grep [command]                                                        | imprimir el historial con ese comando
|telnet towel.blinkenlights.nl                                                  | ver la cuarta película de starwars
|lsblk -fm                                                                      | muestra información de todos los dispositivos de bloque (discos duros, SSD, memorias flash, CD-ROM…) que forman parte del hardware.

