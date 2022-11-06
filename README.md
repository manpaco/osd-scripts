# OSD Scripts

Conjunto de scripts para controlar determinadas funciones de un sistema Linux, con el agregado de mostrar información en pantalla (OSD).

## Dependencias

Todos los scripts dependen de la utilidad <code>aosd_cat</code>.

En el caso de Debian, podemos instalarla desde sus repositorios:

	sudo apt install aosd-cat

## Ejemplo

Cuando cualquiera de los scripts es ejecutado, se mostrará en pantalla informacion relacionada. Por ejemplo:

![volume](/images/osd-cap.png)

## Listado

### volume-control

Hace uso de <code>amixer</code> para controlar el volumen general del sistema.

### take-screenshot

Hace uso de <code>magick</code> para tomar capturas de pantalla.

### backlight-control

Hace uso de <code>xbacklight</code> para controlar la intensidad del backlight de la pantalla.
