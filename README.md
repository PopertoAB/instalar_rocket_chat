# Instalar Rocket.Chat

Es una serie de pasos en español para instalar y modificar rocket.chat en CentOS 7

## Configurar el sistema operativo

Lo primero que hay que hacer es actualizar el sistema, esto se hace con el comando sudo yum -y `sudo yum -y update`

Hay que deshabilitar SELINUX con el comando `setenforce 0` y modificar en el archivo /etc/selinux/config de SELINUX=enforcing a SELINUX=disabled
