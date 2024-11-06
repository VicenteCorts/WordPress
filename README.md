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
https://wordpress.org/download/
- Nos dirigimos a esta dirección y descargamos la versión más reciente de WP
- Extraemos la carpeta wordpress del archivo comprimido que hemos descargado
- Ahora podemos emplear esta carpeta como directorio base de nuestro proyecto en WP (masterphp/wordpress) o cambiar su nombre
- Luego al dirigirnos a la carpeta del proyecto en localhost se nos abrirá directamente el instalador automático de WP.
### Asistente de instalación
- Tendremos que abrir phpmyadmin y crear una BBDD para hacer que esté conectada con WP
- **aprendiendo-wp** y **utf8mb4_general_ci**
- Seguimos con el instalador y le proporcionamos los datos de la BBDD recien creada
> - Nombre de la BBDD: aprendiendo-wp
> - Nombre de usuario (de la BD): root
> - Contraseña (del usuario en la BBDD): 
> - Servidor de la BBDD: localhost
> - Prefijo de tabla: wp_
- Seguimos con la instalación y ahora debemos rellenar los datos de la web
> - título del sitio: SuperBlog
> - Nombre del ususario: admin
> - Contraseña: 1234
> - Correo: admin@admin.com
> - Visibilidad:  la marcamos si es por programar de chill, si la vamos a publicar la desmarcamos
**Acceso: url_finalizada_en/wp-login**

## Clase 495
### La Barra de Herramientas
Barra superior, siempre presente tanto en el backend como en la parte pública, siempre y cuando estemos loggeados.

## Clase 496
### Escritorio del Panel






















