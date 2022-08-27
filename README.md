Soy Silvia! Tengo 36 años, de Uruguay. Hace años que me dedico al rubro de Networking y soluciones de Comunicaciones Unificadas y hoy decidi hacer un cambio de rubro y volcarme por esta nueva área que tanto me apasiona.
-----------------------------------------------------------------------------------------------------------
¿Cómo nace la idea de este proyecto?

Surge de la necesidad de que la organizacion Zonta, requiere un sitio web para la región Sudamerica y en español. Para este trabajo final se tomó información del sitio Zonta Internacional, pero se irá adaptadando con el cliente final para incorporar la información deseada.
-----------------------------------------------------------------------------------------------------------
¿Qué contiene este repositorio?

- Wireframes: Wireframes.pdf 
Se suben los entregados al inicio del proyecto, con el correr del mismo, se han modificado los vínculos de "Ingresar" y "Queres Donar?" a un nuevo   submenú denominado "Mi Zonta" dentro del Nabvar para que en vista mobile quedaran todas las opciones dentro del menú hamburguesa. 
- Deploy de todo el sitio web.
- Presupuesto: Presupuesto-ZontaSudamerica.pdf
- SEO: Consideraciones_para_Seo.txt
- gitignore
- Link al servidor externo: https://zontasudamerica.000webhostapp.com/ 
-----------------------------------------------------------------------------------------------------------
¿Cómo esta conformado el sitio web?

Encontraremos 8 páginas web:

- index --> Página de inicio.
- nuestras_causas, nuestros_programas, novedades_y_eventos y sobre_nosotros --> Páginas informativas.
- contacto, ingresar y donar --> Formularios
-----------------------------------------------------------------------------------------------------------
¿Cómo está pensado el código en mi proyecto?

Se definen los siguientes partials genéricos para planificar el diseño del mismo:

- _header: Se definen las clases utilizadas para el encabezado de todas las páginas del sitio.
- _main: Se definen todas las clases del main de todas las páginas del sitio.
- _footer: Se definen las clases del footer para todas las páginas del sitio.

Se definen los siguientes partials específicos:

- _vars: Se definen variables para definir el esquema de colores específicos y para los tipos de fuentes.
- _fonts: Se importan las fuentes de google fonts y se definen las clases para las mismas, encontrando extends de clases base e includes de mixins definidios en el partial _mixins
- _mixins: Se define un map para el esquema de colores complejos (degrades), las clases base y los mixins.
- _animaciones: Se definen todas las animaciones aplicadas en todas las páginas del sitio web.
- _mediaquerys: Se definen todos los mediaquerys y sus correspondientes adaptaciones para que el sitio web sea responsive.
- _global: Se definen las adaptaciones para etiquetas semanticas y no semanticas.
