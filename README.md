## Slideshared

Script para la descarga automatica y consecutiva de imagenes de diapositivas en "www.slideshare.net".

### Instalacion

Se descarga el archivo "slideshared" y luego se le provee permisos de ejecucion.

```$ chmod +x slideshared```

Si desea llamar al script desde cualquier ubicacion de su sistema, debe [incluir la ruta del directorio contenedor del script en la variable de entorno $PATH](http://www.troubleshooters.com/linux/prepostpath.htm#_singleuser).

### Ejemplos de uso

Para descargar una diaposiva completa, desde la primera imagen y en el directorio actual

```$ slideshared -u "http://image.slidesharecdn.com/introductiontolisp-100316055809-phpapp01/95/lisp-introduction-to-lisp-1-728.jpg?cb=1268737125"```

esto crea una carpeta con el nombre "lisp-introduction-to-lisp" en el directorio actual con las imagenes numeradas del 1 en adelante.

Para elegir la ubicacion y nombre del directorio, debe especificar una ruta de descarga con la opcion "-O"

```$ slideshared -u "http://image.slidesharecdn.com/introductiontolisp-100316055809-phpapp01/95/lisp-introduction-to-lisp-1-728.jpg?cb=1268737125" -O ~/myslide/```

esto crea la carpeta "myslide" en el directorio home del usuario actual con todas las imagenes.

Para obtener todas las opciones y el modo de uso se utiliza la opcion "-h".

**EOF**
