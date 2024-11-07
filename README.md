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
Panel lateral del apartado Admin o Backend. Aquí es donde se realizan las configuracioens e instalaciones necesarias para ir editando nuestra web

## Clase 497
### Crear Nuevas Entradas
Añadir nueva -> Para crear nueva entrada
- Creamos nuestra nueva entrada y trasteamos con ella y las posibilidades que ofrece
- interesante el botón de leer más dentro de los Posts

## Clase 498
### Entradas Avanzadas
- Categorías
- Editor de código
- Etiquetas SEO (SEO y categorización)
- Imagen destacada

## Clase 499
### Categorías Creación y Gestión
Pdemos crear categorias en su apartado.
- El slug es el segmento de url que queremos que aparezca para referenciar a una categoría
- En etiquetas el funcionamiento es el mimso, sirve para mejorar el SEO

## Clase 500
### Medios
Aquí tendremos todos los archivos que subamos desde imágenes hasta pdf audios o lo que sea

## Clase 501
### Páginas
Funciona igual que la parte de entradas. Aquí es donde se elaboran las paginas de neustra web. Posteriormente deberan ser añadidas al menú en otra de las secciones del panel de Administrador

## Clase 502
### Gestionar Comentarios
Sobre todo interesante para "pendiente de revisión" o "Spam"

## Clase 503
### Ajustes Generales
- Cambiar Nombre de la web
- Cambiar Descripción de la web
- Cambiar la URL (por si cambiamos de dominio)
- Dirección de correo, llegan todas las notificiaciones del sitio web
- Miembros: cualquiera puede registrarse
- Usuarios (sin permisos por default)
- Idioma
- Zona horario
- Semana
- (...)
### Ajustes de Escritura
- Categoría predeterminada
- (...)
### Ajustes de Lectura
- Portada
- máximo de entradas a mostrar
- texto completo o Resumen (por entrada)
- Motores de búsqueda

## Clase 504
### Ajustes de Comentarios
- Avisar a sitios web cuando usamos enlaces suyos
- comentarios en articulos nuevos
- datos de autores
- usuarios registrados
- aprobar comentarios
- Moderación de comentarios
- Lista negra
- Avatares

## Clase 505
### Ajustes de Medios 
- Caracterísiticas de los elementos que subimos a la biblioteca de Medios (imágenes menos pesadas)
- Organización de los medios, por fecha de subida

## Clase 506
### Ajustes de Enlaces Permanentes
- Para webs de noticias recomienda "Día y nombre"
- Para webs con contenido evergreen "Nombre de la entrada" -> Mejor puntuación SEO google para contenido evergreen

## Clase 507
### Ajustes de Privacidad
- Podemos crear una página para política de privacidad
- También se puede editar y publicar con normalidad

## Clase 508
### Herramientas
- Importar de otra plataforma o wordpress (se hace mediante instalación de plugins)
- Exportar, podemos crear un archivo de exportación de nuestro wp a nivel completo, entradas u otro tipo de contenido seccionado -> este tipo de archivos se puede emplear para la importación (punto anterior)
- Exportar datos personales
- Borrar Datos Personales
- **Conforme añadamos plugins aquí irán apareciendo más apartados para configuración de los mimsos**

## Clase 509
### Usuarios
Podemos administrar a cualquier usuario, nuestra web no tiene por qué tener siempre un apartado de registro.
- Suscriptor: no hace nada
- Colaborador: tiene acceso a comentarios, entradas y poco más
- Autor: igual que colaborador pero con acceso al apartado de **Medios**
- Editor: Añadir categorías, páginas, gestion en general
- Administrador: control total

## Clase 510
### Instalar y configurar temas
Poca información útil sobre Temas (Victor Robles)

## Clase 511
### Widgets
BLoques de widgets, más interesante de lo que esperaba, yo no los había usado antes.

## Clase 512
### Menús
Poca información útil

## Clase 513
### Editor de Código
MUY INTERESANTE ESTO SI

## Clase 514
### Plugins
SEO: YoastSEO

## Clase 515
### Plugins Interesantes
Explicación de Yoast Seo (...)
Contact form 7 -> Para formularios de contacto

## Clase 516
### Más Plugins Interesantes
**La web se va ralentizando cuanto más elementos se le van añadiendo**
- Es importante por ello intalar un sistema de caché: **WP Super Caché**
- Para artículos relacionados: **WP Related Post**
- Antispam: **Anti Spam**
- Cookies: **GDPR Cookie Consent**
- RRSS: **Social Bar**
- **Woocommerce**
- Learning
- etc.






