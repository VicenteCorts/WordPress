# Wordpress - Victor Robles
## Clase 493
### Configuraciones Previas 
Antes de instalar WordPress debemos asegurarnos de que tenemos una serie de módulos de apache instalados y modificar en el apartado de php el **post_max_size**
- En los módulos de apache debemos tener instalado:
	+ rewrite_module
- En el apartado de configuraciones de PHP debemos:
	+ post_max_size = 256M (o más)
	+ upload_max_filesize = 256M (o más)
	+ date.timezone = Europe/Madrid

## Clase 494
### Instalación WordPress
