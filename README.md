# Plantilla de Página Web - DISTRICOL

¡Bienvenido! Esta plantilla ha sido diseñada para servir como base de tu sitio web principal, incorporando un sistema de diseño modular y componentes reutilizables que garantizan un desarrollo rápido y una apariencia consistente.

## Estructura del Proyecto

El proyecto(template) está compuesto por dos archivos principales:

1.  `index.html`: El archivo de la página web, que muestra componentes visuales. Contiene todo el contenido, desde el encabezado hasta el pie de página. Está estructurado con etiquetas HTML5 semánticas y clases CSS descriptivas para facilitar la edición.
2.  `template.css`: La hoja de estilos. Aquí se define el sistema de diseño completo, incluyendo la paleta de colores, la tipografía y los estilos de todos los componentes.

## Componentes y Clases Clave

Esta plantilla utiliza un enfoque basado en clases para que puedas aplicar estilos predefinidos a cualquier elemento. A continuación, se detallan las clases más importantes que puedes reutilizar:

### 1. Clases de Estructura y Contenedores

-   `.container`: El contenedor principal de ancho fijo que centra el contenido de cada sección. Úsalo para envolver el contenido dentro de cualquier sección.
-   `.seccion`: La clase base para cada bloque principal de contenido.
-   `.seccion-blanca`, `.seccion-gris`, `.seccion-oscura`, `.seccion-amarilla`: Clases modificadoras para cambiar el color de fondo de una sección completa.

### 2. Títulos y Párrafos

-   `.titulo-principal`: Aplica un estilo grande y centrado para los títulos principales de la página.
-   `.card-title`: Estilo de título específico para los encabezados dentro de tarjetas o componentes.
-   `.intro-text`: Utilízala para párrafos introductorios largos que requieren un formato especial.

### 3. Sistema de Botones

Los botones son un elemento crucial para la interacción. Puedes usarlos con la etiqueta `<button>` o `<a>` y aplicar una de las siguientes clases:

-   `.boton`: Clase base para todos los botones.
-   `.boton-primario`: Estilo de botón principal con el color de la marca.
-   `.boton-secundario`: Estilo de botón con un color complementario.
-   `.boton-outline`: Estilo de botón con borde y fondo transparente.
-   `.botones-grupo`: Clase que organiza los botones en un grupo con espaciado uniforme.

### 4. Tarjetas y Grillas

La plantilla incluye clases para crear diseños en formato de tarjeta:

-   `.card`: La clase para el contenedor de una tarjeta. Ya incluye sombra y un efecto de elevación al pasar el mouse (`hover`).
-   `.card-grid`: Contenedor para crear una grilla responsiva de tarjetas. Simplemente coloca múltiples elementos `.card` dentro.
-   `.icono-card`: Una tarjeta especializada para mostrar un ícono, un título y una descripción.
-   `.step-card`: Un componente visual para mostrar un proceso o una serie de pasos numerados.

### 5. Variables CSS Personalizadas

El archivo `template.css` utiliza **Variables CSS** (o Propiedades Personalizadas) para definir la paleta de colores y las fuentes. Si deseas cambiar la apariencia global de la plantilla, solo necesitas modificar los valores en el bloque `:root` al inicio del archivo `template.css`.

```css
:root {
    /* Paleta de colores */
    --color-primario: #ffcf00; /* Color principal de la marca */
    --color-texto: #454545;
    /* ... y otras variables ... */
}
```

Al modificar estos valores, los cambios se reflejarán automáticamente en toda la página.

## Animaciones

La plantilla incluye animaciones de aparición suaves al hacer scroll, lo que mejora la experiencia del usuario.

### ¿Cómo funcionan?

La magia ocurre en el archivo index.html con un poco de JavaScript. Un IntersectionObserver detecta cuándo un componente entra en la vista del usuario y le aplica la clase .fade-in-up para animarlo.

### ¿Qué elementos se animan?

Esta animación se aplica a las clases .card, .icono-card y .step-card por defecto. No necesitas hacer nada para que funcione.

### Puesta en Marcha

Para visualizar la plantilla en tu navegador, simplemente abre el archivo index.html en tu navegador web de preferencia (Google Chrome, Firefox, etc.) o ingresa a la página subida con github pages mediante la url: https://juan17informatico.github.io/template-districol/