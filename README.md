# Archivo de configuración de conky
Según [Wikipedia](https://es.wikipedia.org/wiki/Conky_%28software%29);

> **Conky** es un software monitor del sistema [libre y de código abierto](https://es.wikipedia.org/wiki/Software_libre "Software libre") para el [sistema de ventanas X](https://es.wikipedia.org/wiki/Sistema_de_ventanas_X "Sistema de ventanas X"). Está disponible para [Linux](https://es.wikipedia.org/wiki/Linux "Linux"), [FreeBSD](https://es.wikipedia.org/wiki/FreeBSD "FreeBSD"), y [OpenBSD](https://es.wikipedia.org/wiki/OpenBSD "OpenBSD"). Conky es altamente configurable y permite monitorear algunas variables del sistema incluyendo el estado de la CPU, memoria disponible, espacio en la partición de intercambio,


# Qué contiene este archivo?

El archivo de configuración del repositorio está basado en **[ESTE](https://www.opendesktop.org/p/1282146/)** de opendesktop.org. Que a su vez, debe estar forkeado de varios mas. Es la versión más simple de configuración de conky. 
Muestra el consumo de CPU y RAM, procesos corriendo, información sobre la conexión a la red, y el uso de los discos rígidos.
Funciona en mi notebook corriendo Ubuntu 18.10, no doy garantías que funcione en la tuya :p

# Instalación
En distribuciones con derivadas de Debian:

```sudo apt-get install conky conky-all```

Copiar el archivo conkyrc a ```/~```.
Renombrarlo a ```.conkyrc```, para ocultarlo. Para mostrar archivos ocultos, presionar ```ctrl+H``` en Nautilus.
Luego, agregar ```conky``` en ```Aplicaciones al Inicio```.

