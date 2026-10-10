# La Forja de Velkarys — E-commerce Front-End

Este repositorio corresponde al proyecto Front-End desarrollado para la entrega. Consiste en un sitio web multipágina de comercio electrónico enfocado en un catálogo de accesorios artesanales para juegos de rol de mesa (TTRPG).

## Descripción del Proyecto
El proyecto simula una tienda en línea orientada a la venta de productos de fabricación manual (como dados de resina, encuadernaciones y artículos coleccionables). El objetivo principal de esta etapa es la maquetación, el diseño responsivo y la estructuración semántica, utilizando tecnologías nativas de la web y dejando preparada la arquitectura para futuras interacciones con JavaScript.

## Estructura del Sitio
El sitio web cuenta con una navegación multipágina unificada:
* **Inicio (`index.html`)**: Página principal con la presentación de la marca, una sección de productos destacados utilizando **Flexbox** y un bloque de crónicas/reseñas estructurado mediante **CSS Grid**.
* **Inventario (`inventario.html`)**: Catálogo general de productos con una barra de filtrado estática y etiquetas de disponibilidad de stock.
* **El Taller (`taller.html`)**: Sección informativa orientada al proceso de fabricación artesanal, con un diseño de layout mixto.
* **Contacto (`contacto.html`)**: Formulario de consultas y encargos especiales integrado con el servicio externo **Formspree**.

## Tecnologías y Stack Utilizado
* **HTML5**: Estructura semántica con etiquetas estandarizadas (`header`, `main`, `section`, `article`, `nav`, `footer`).
* **CSS3**: Estilos modularizados en una hoja centralizada (`styles.css`), implementando variables CSS (`:root`), scrollbar personalizado y tipografías de Google Fonts (*Cinzel Decorative* e *IM Fell English*).
* **Flexbox y CSS Grid**: Modelos de diseño adaptables para la distribución de tarjetas de productos y grillas de contenido.
* **Media Queries**: Puntos de quiebre responsivos para asegurar la correcta visualización en dispositivos móviles y de escritorio.
* **Formspree**: Gestión del envío de correos electrónicos desde el formulario de contacto.

## Proyecto Publicado
El sitio se encuentra optimizado y desplegado en línea para su visualización:
👉 [Ver sitio en producción](https://tu-enlace-de-deploy.com)
