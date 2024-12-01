Estructura del Proyecto El proyecto está organizado en una estructura de carpetas para facilitar su mantenimiento y escalabilidad. La estructura es la siguiente:

markdown Copy code

index.html
assets/
css/
styles.css (Estilos personalizados del sitio)
images/
1.jpg (Imágenes de productos en formato JPG)
2.jpg
...
9.webp (Una imagen en formato WebP)
fonts/ (Opcional: Fuentes personalizadas)
pages/
productos.html (Página de galería de productos)
presupuesto.html (Página de formulario para presupuestos)
contacto.html (Página de contacto con mapa y datos) Páginas y Funcionalidades
Inicio (index.html) Contiene información sobre la empresa con tres secciones principales: Introducción a la empresa. Servicios destacados. Opiniones de clientes. Incluye un menú de navegación para acceder a las demás páginas. Un pie de página con enlaces a redes sociales, dirección y aviso legal.
Productos (productos.html) Muestra una galería de imágenes en una cuadrícula, con 9 imágenes (8 en formato JPG y 1 en WebP). Las imágenes están correctamente dimensionadas en HTML para optimizar el uso de memoria.
Presupuesto (presupuesto.html) Incluye un formulario con los siguientes campos: Nombre Email Teléfono Un campo de texto multilínea para información adicional. Un checkbox para aceptar la política de privacidad (requerido para enviar el formulario).
Contacto (contacto.html) Presenta un mapa de la ubicación de la empresa (imagen estática en formato PNG o JPG). Detalles de contacto de la empresa. Estilo y Diseño El sitio utiliza Bootstrap 5 para la maquetación y componentes responsivos. Colores seleccionados siguiendo una paleta complementaria para un diseño atractivo y profesional. Todo el CSS está separado en el archivo styles.css dentro de la carpeta assets/css. Requisitos y Validación HTML validado: Todos los archivos HTML cumplen con las reglas del W3C Validator. Estilos externos: Ningún estilo está definido en línea o en los archivos HTML. Navegación funcional: El menú de navegación incluye enlaces correctamente enlazados y resalta la página activa. Instrucciones para Visualizar el Proyecto Clona este repositorio: bash
git clone <URL_DEL_REPOSITORIO> Abre el archivo index.html en tu navegador para visualizar la página principal. Navega por las demás páginas utilizando el menú de navegación. Características Adicionales Footer fijo: El pie de página permanece siempre en la parte inferior de la página. Diseño responsivo: El sitio se adapta a diferentes tamaños de pantalla gracias a Bootstrap. Accesibilidad: Uso de etiquetas semánticas para mejorar la experiencia del usuario y SEO. Autor Proyecto desarrollado por [AGUSTIN MOTUHU OYEGUE ONGUENE] como parte del trabajo final para un curso de desarrollo web.