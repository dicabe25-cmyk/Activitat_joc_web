# Activitat_joc_web
Proyecto: Librería "Página en Blanco"
Este proyecto consiste en una interfaz web estática para una librería, compuesta por tres páginas HTML interconectadas que comparten una única hoja de estilos CSS. El objetivo es demostrar un diseño consistente, responsivo y profesional utilizando una arquitectura de estilos centralizada.

Estructura del Proyecto
La organización de archivos es la siguiente:

index.html: Página de inicio con novedades y banners.

catalogo.html: Listado de libros disponibles con filtros básicos.

contacto.html: Formulario de suscripción y ubicación.

css/

styles.css: Hoja de estilos compartida para todo el sitio.

img/: Directorio para portadas de libros y logotipos.

Descripción de las Páginas
1. Inicio (index.html)
Es la carta de presentación de la librería. Contiene:

Hero Section: Un mensaje de bienvenida con una imagen de fondo inspiradora.

Sección de Novedades: Un grid con los 3 libros más destacados del mes.

Llamada a la acción (CTA): Botón directo hacia el catálogo completo.

2. Catálogo (catalogo.html)
El corazón de la tienda. Presenta:

Grid de Productos: Una disposición organizada de tarjetas de libros.

Tarjetas (Cards): Cada libro incluye imagen, título, autor, precio y un botón de "Añadir al carrito".

Efectos Hover: Las tarjetas se elevan sutilmente al pasar el ratón para mejorar la interactividad.

3. Contacto (contacto.html)
Página funcional que incluye:

Formulario: Campos para nombre, correo y mensaje, validados por HTML5.

Información de tienda: Horarios de atención y redes sociales.

Mapa: Espacio reservado para la ubicación física.

Estilo Compartido (styles.css)
Para mantener la identidad visual, el archivo CSS centraliza los siguientes aspectos:

Sistema de Diseño
Paleta de Colores: Uso de variables CSS para facilitar cambios globales.

Primario: #2c3e50 (Azul medianoche para textos y navegación).

Acento: #e67e22 (Naranja para botones y alertas).

Fondo: #f4f4f4 (Gris claro para descanso visual).

Tipografía: Importación de Google Fonts (ej. 'Playfair Display' para títulos y 'Lato' para cuerpo).

Componentes Globales Reutilizados
Navbar: Menú de navegación superior que se repite exactamente igual en las tres páginas.

Footer: Pie de página con derechos de autor y links rápidos.

Botones: Clase única .btn-primary que garantiza que todos los botones del sitio tengan el mismo redondeo, sombra y transición.

Instrucciones de Uso
Instalación: Clona este repositorio o descarga los archivos.

Visualización: Abre el archivo index.html en cualquier navegador moderno (Chrome, Firefox, Edge).

Edición de Estilos: Si deseas cambiar el color principal de toda la web, solo debes editar la variable en la línea 1 de styles.css:

CSS

:root {
    --color-primario: #2c3e50; /* Cambia este valor */
}
 Tecnologías Utilizadas
HTML5: Estructura semántica (header, nav, main, section, footer).

CSS3: Flexbox y CSS Grid para el layout responsivo.

Google Fonts: Para una tipografía elegante y legible.
