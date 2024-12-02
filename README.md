# Proyecto: “Desarrollo de una Aplicación Web Completa con HTML5 y CSS3”

## por Antonio José Monge Monge

**Descripción del Proyecto:**

Desarrollar una aplicación web usando los conocimientos de HTML5 y CSS3 vistos en clase. Ponerlos en práctica de manera avanzada, enfocandose en la estructura de esta web para que sea *responsive*. Siguiendo una serie de objetivos y de restricciones, siendos estos/as:

**OBJETIVOS:**

- Analizar y aplicar las características de diferentes lenguajes de marcas en el desarrollo de una aplicación web.
- Identificar y utilizar etiquetas y atributos HTML5 de manera efectiva.
- Aplicar hojas de estilo CSS3 para mejorar la presentación y usabilidad de la aplicación.
- Validar y optimizar los documentos HTML y CSS creados, asegurando la conformidad con los estándares web.
- Fomentar la autonomía y capacidad de gestión del alumnado en la realización del proyecto.

**RESTRICCIONES:**

- El uso de la etiqueta *STYLE*
- *Divs* se usarán *section* por ejemplo
- *Pxs* se usarán *rem*
- *IDs* en su lugar, utilizaré *class*
- *Buttons* pudiendo usar directamente enlaces

## Fase 1: Planificación del Proyecto (Wireframe y Estructura HTML)

El objetivo de esta fase es planificar la estructura y el diseño de la aplicación web antes de empezar a desarrollarla. Para ello, he realizado un esquema detallado del contenido y diseño a implementar en la web, utilizando **Balsamiq** para crear el wireframe. Esta planificación me permitirá organizar de forma efectiva los elementos clave de la página y estructurar el HTML de manera correcta.

### 1. Análisis de requisitos y objetivos del proyecto

Lo primero que hice fue analizar el enunciado del proyecto para entender qué debo hacer y qué características debe tener mi aplicación web. En este paso, definí los **requisitos funcionales y no funcionales** del proyecto, los cuales me ayudaron a establecer qué contenido debe tener la web y qué funcionalidades son esenciales, como la navegación entre secciones y la presentación de contenido multimedia.

- **Requisitos funcionales**: La web debe contener varias páginas con contenido organizado, como "Inicio", "Últimos Lanzamientos", "Próximos Lanzamientos" y "Recomendaciones". Además, debe ser fácil de navegar y tener una interfaz responsiva para adaptarse a diferentes dispositivos.
  
- **Requisitos no funcionales**: La web debe ser accesible para personas con discapacidades, debe cargarse rápidamente y ser compatible con los navegadores más comunes.

También elegí las tecnologías que voy a usar, es decir, **HTML5** y **CSS3**, porque son lenguajes estándar para crear páginas web. HTML me permitirá estructurar el contenido de la web de manera semántica, mientras que CSS me ayudará a darle estilo y hacerla responsiva.

### 2. Creación de un wireframe en Balsamiq

Una vez definidos los requisitos y objetivos, utilicé **Balsamiq** para crear un wireframe, que es un esquema visual de la página web. Este wireframe me permitió organizar los elementos principales que tendrá la web, como el **encabezado**, el **menú de navegación**, el **área de contenido principal**, y el **pie de página**.

El wireframe refleja la estructura básica de las páginas, mostrando cómo estarán distribuidos los elementos en cada pantalla. A continuación, te muestro cómo quedaría el diseño de la página de inicio:

- En la parte superior estará el **encabezado** con el logo y el menú de navegación.
- Bajo el encabezado, se verá una serie de **secciones** como "Últimos Lanzamientos", "Próximos Lanzamientos" y "Recomendaciones".
- Al final de la página, incluiré un **pie de página** con derechos de autor y enlaces de contacto.

Este paso es muy importante porque me da una visión clara de cómo se verá la web antes de comenzar a escribir el código.

Más abajo te muestro los prototipos que hice en Balsamiq, hay que tener en cuenta que de cara a la versión final si que se cambió algún que otro detalle. Bien por demasiada ambición o simplemente por comodidad.

![Pagina Principal](LLMM-PROYECTO/proyectoLLMM2425_AMM/wireframe/PÁGINA_PRINCIPAL.png)

![Pagina de Registro](LLMM-PROYECTO/proyectoLLMM2425_AMM/wireframe/REGISTRO.png)

### 3. Estructura HTML planificada

En esta parte de la fase, planifiqué cómo voy a estructurar el código HTML. Para ello, he identificado las **etiquetas y atributos** que utilizaré en cada sección de la web.

Por ejemplo, para el **encabezado**, utilizaré la etiqueta `<header>`, dentro de la cual irán el logo y el menú de navegación. El menú de navegación se organizará con las etiquetas `<nav>`, usando `<href>` para cada enlace.

Cada **sección de contenido** (como "Últimos Lanzamientos") la marcaré con la etiqueta `<section>`, y cada título de sección irá dentro de una etiqueta `<h2>`. Además, las imágenes de las secciones se insertarán con la etiqueta `<img>`, siempre añadiendo un atributo `alt` para la accesibilidad.

El **pie de página** se estructurará dentro de una etiqueta `<footer>`, donde también incluiré el texto de derechos de autor y los enlaces adicionales.
