# DebianPostIntallScript

###### Unicamente para Debian 8 "Jessie" y adelante.

**Se requiere ser root para instalarse**, entrando en la terminal con el comando su, además de contar con el disco de instalación del sistema, ya que algunos paquetes lo necesitan en caso de no haber utilizado una imagen de netist. 

Para ejecutarlo: ir a la carpeta donde se tenga guardado, y ejecutar el comando **./debianPackages A B C D E F G**

En donde:
* A es 1 si se quiere instalar CUDA y además se tiene una tarjeta de video NVIDIA o 0 si no"
* B es 1 si se quire instalar LATEX para escribir papers o 0 si no"
* C es 1 si se quiere instalar STEAM para juegos o 0 si no"
* D es 1 si se quiere el programmer pack (ruby, octave, R, git, vim-python-compiled, wireshark) 0 si no"
* **¡ATENCIÓN! ESTA OPCIÓN DESINSTALARA *gedit* PARA AGREGAR ATOM**
* E es 1 si no se instaló Netbeans ni CUDA y se quiere quitar el otro java de linux o 0 si no quiere quitar"
* F es 1 si se quiere instalar Netbeans con Java EE, 2 si se quiere con Java SE, 3 si se quiere con C/C++, 4 si se quiere con HTML% & PHP, 6 si se quiere el paquete completo o 0 si no"
* G es 1 si se quiere instalar Spotify y Skype o 0 si no"

El script por default instalará los siguientes paquetes:
* *g++*, compilador de c++
* *firmware-iwlwifi*, el driver para el uso de wifi
* *k3b*, para quemar cd/dvd
* *xfce4-xkb-plugin*, configuración del teclado
* *kingsoft office*, variación de Office de Windows, muy similar
* *libcurl3*, para la dependencia del navegador Google Chrome
* *Google Chrome*
* *freeglut3*, paquete de OpenGL, se instalan el paquete de developer también
* *Java y Javac*, directo de la página de oracle
* *nmap*, utilizado para cerrar los servicios inseguros
* *Adt Bundle Android*

El script también removerá los paquetes inseguros:
* *ftp*
* *telnet*
* *samba*
* *transmission-gtk*
* *pprtp-linux, network-manager.pptp network-manager-pptp-gnome*
* *ppp pppoeconfig pppconfig*
* *rsync*
* *vinagre*
* *blueman*
* *bluez*, en caso de estar instalado
* *xchat*, en caso de estar instalado
