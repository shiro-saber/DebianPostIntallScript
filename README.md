# DebianPostIntallScript

Unicamente para Debian 8 "Jessie" y adelante.

Se requiere ser root para instalarse, entrando en la terminal con el comando su, además de contar con el disco de instalación del sistema, ya que algunos paquetes lo necesitan.

Para ejecutarlo se debera de ir a la carpeta donde se tenga guardado, y ejecutar el comando ./debianPackages A B C D E F

En donde:
A es 1 si se quiere instalar CUDA y además se tiene una tarjeta de video NVIDIA o 0 si no"
B es 1 si se quire instalar LATEX para escribir papers o 0 si no"
C es 1 si se quiere instalar STEAM para juegos o 0 si no"
D es 1 si se quiere el programmer pack (ruby, octave, R, git) 0 si no"
E es 1 si no se instaló Netbeans ni CUDA y se quiere quitar el otro java de linux (ya que si se instalará el Java de Oracle) o 0 si no quiere quitar"
F es 1 si se quiere instalar Netbeans o 0 si no"
