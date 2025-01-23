README: Página web de socio Cordientrega.


Descripción

Esta página web está diseñada para permitir la compra y venta de productos en su comunidad bajo la plataforma Cordientrega. Los usuarios pueden publicar productos, buscar artículos a la venta y contactar a vendedores mediante enlaces a WhatsApp. Además, se integra con la red Lightning para permitir pagos rápidos y eficientes en Bitcoin.

Funcionalidades

Publicación de productos: Los usuarios pueden publicar productos para la venta a través de un formulario, especificando título, precio, celular, ubicación y descripción.

Búsqueda de productos: Se incluye un buscador de productos donde los usuarios pueden buscar por palabras clave.

Pagos en Bitcoin: Los productos muestran su precio en COP y su equivalente en satoshis (Bitcoin en la red Lightning).

Enlace a WhatsApp: Cada producto tiene un enlace que lleva al usuario a una conversación de WhatsApp con el vendedor.

Listado de contactos: Se muestra una tabla con contactos de personas relevantes que venden productos o servicios.

Responsive: La página está optimizada para dispositivos móviles y escritorio, asegurando una buena experiencia de usuario.


Estructura del Código

HTML

La página está estructurada utilizando HTML5 con la siguiente jerarquía:

Head: Contiene metadatos como el título, descripción, enlaces de redes sociales (Open Graph y Twitter), herramientas de análisis (Google Analytics, Facebook Pixel) y favicon.

Cuerpo: La estructura principal de la página incluye:

Un formulario para publicar productos.

Un buscador de productos y contactos.

Listado de productos con precios en COP y Lightning.

Una tabla con contactos relevantes.

Un pie de página con términos y condiciones y derechos de autor.



CSS

La página tiene un estilo limpio y moderno con los siguientes detalles:

Tipografía: Uso de Arial, sans-serif.

Colores: Fondo claro con botones oscuros para resaltar las acciones.

Layout: Diseño responsivo con contenedores centrados y bien espaciados.


JavaScript

El JavaScript se encarga de las siguientes funcionalidades:

Cálculo de precios en Lightning: Obtiene el precio del Bitcoin en USD y el tipo de cambio COP-USD desde APIs externas (CoinGecko) y calcula el precio de cada producto en satoshis.

Actualización de precios: Calcula los precios de los productos en Bitcoin y los actualiza dinámicamente en la página.

Búsqueda de productos y contactos: Permite a los usuarios filtrar los productos y contactos visibles en la página según sus preferencias.


Tecnologías utilizadas

HTML5: Para la estructura de la página.

CSS3: Para el diseño visual.

JavaScript: Para la funcionalidad interactiva (precios en Lightning, búsqueda, etc.).

APIs externas:

CoinGecko API: Para obtener el precio de Bitcoin y el tipo de cambio COP-USD.

Formspree: Para manejar el formulario de contacto.

WhatsApp API: Para enlazar con conversaciones en WhatsApp.



Instalación

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. Clona el repositorio:

git clone https://github.com/tu-usuario/contraentrega.git


2. Abre el archivo HTML:

Navega a la carpeta del proyecto y abre el archivo index.html en tu navegador favorito.



3. Configura las APIs:

Asegúrate de que las claves API de CoinGecko y otras herramientas de terceros estén correctamente configuradas.



4. Personaliza los enlaces:

Actualiza los enlaces y las imágenes a tus URLs correspondientes.




Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de hacer un fork del repositorio y enviar un pull request con mejoras o nuevas funcionalidades. Asegúrate de seguir las mejores prácticas de desarrollo y de documentar adecuadamente cualquier cambio realizado.

Licencia

Este proyecto está licenciado bajo la licencia MIT.

Contacto

Correo electrónico: info@cordientrega.com

Sitio web: www.cordientrega.com


¡Gracias por usar Cordientrega!

