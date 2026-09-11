# Naff Style

Sitio web sobre **Naff Style**, marca de cultura urbana que combina la venta de ropa con la promoción de artistas independientes y la organización de eventos de freestyle.

## Descripción

Naff Style es una plataforma independiente construida en torno a tres líneas de actividad:

| Área | Descripción |
|---|---|
| Ropa | Línea propia de prendas orientada a transmitir identidad y actitud. Constituye el eje principal del proyecto. |
| Promoción de artistas | Espacio de visibilidad y apoyo para talento emergente dentro de la escena urbana. |
| Batallas de gallos | Organización y sponsorización de *Laguna Battles*, evento de freestyle e improvisación. |

Este repositorio contiene la implementación del sitio web corporativo, desarrollado con HTML5 y CSS3, sin frameworks ni dependencias externas.

## Características

- Diseño maquetado íntegramente en HTML y CSS puro mediante requerimientos y limitaciones del profesorado.
- Cabecera de navegación común a todas las secciones internas.
- Formulario de contacto con validación de campos mediante atributos nativos de HTML.
- Contenido multimedia embebido (YouTube, Google Maps) mediante `iframe`.
- Estructura de páginas independientes por sección, facilitando el mantenimiento del contenido.

## Estructura del proyecto

```
naff-style-web/
├── index.html            Página principal
├── proyectos.html        Resumen de las líneas de actividad de la marca
├── ropa.html             Catálogo de producto
├── artistas.html         Sección de artistas promocionados
├── batallas.html         Información sobre Laguna Battles
├── nosotros.html         Sobre la marca
├── contacto.html         Formulario de contacto
├── css/
│   └── styles.css        Hoja de estilos global
├── img/                  Recursos gráficos (logos, iconos, imágenes)
└── README.md
```

## Páginas del sitio

### `index.html` — Inicio

Página de entrada al sitio. Presenta el logotipo de la marca y un menú con enlaces a Proyectos, Sobre Nosotros y Contacto. Es la única página que no incluye la cabecera estándar del resto del sitio.

### `proyectos.html` — Proyectos

Presentación de las tres líneas de actividad de la marca (ropa, artistas, batallas de gallos), cada una con una breve descripción y un enlace hacia su página de detalle correspondiente.

### `ropa.html` — Catálogo de ropa

Catálogo de productos organizado en tabla, con imagen, nombre, descripción corta y descripción extendida para cada prenda.

### `artistas.html` — Artistas

Perfiles de los artistas promocionados por la marca. Cada perfil incluye nombre, biografía breve, enlaces a redes sociales (Instagram, YouTube) y un vídeo de YouTube incrustado.

### `batallas.html` — Batallas de gallos

Información sobre *Laguna Battles*, el evento de freestyle organizado y patrocinado por la marca. Incluye una explicación del formato de las batallas, enlaces a las redes sociales del evento (Instagram, YouTube, DailyRapp) y un mapa con la ubicación donde se celebra.

### `nosotros.html` — Sobre nosotros

Contenido textual sobre el origen de la marca, sus valores y filosofía, y cómo se reflejan en cada una de sus tres líneas de actividad: ropa, promoción de artistas y batallas de gallos.

### `contacto.html` — Contacto

Enlace directo al Instagram de la marca y un formulario de contacto con los siguientes campos:

| Campo | Descripción |
|---|---|
| Nombre | Campo de texto obligatorio |
| Correo electrónico | Campo de email obligatorio, con validación de formato |
| Motivo | Selección entre varias opciones (información general, ropa, artistas, batallas, otro) |
| Asunto | Campo de texto libre para detallar la consulta |

El formulario envía los datos por correo electrónico al abrir el cliente de correo del usuario.

### Elementos comunes

Todas las páginas, salvo la de inicio, comparten una cabecera con el logotipo (enlazado a inicio) y el menú de navegación a Proyectos, Sobre Nosotros y Contacto, así como una imagen ilustrativa al comienzo de cada sección.

## Tecnologías utilizadas

- HTML5
- CSS3
- Integraciones externas: YouTube Embed, Google Maps Embed

## Autoría

Proyecto desarrollado en el marco de la asignatura de Lenguajes de Marcas.
