# Portafolio UX/UI

Sitio estático de Rusmeri Cárdenas. Se publica con GitHub Pages en https://rusmericar.github.io.

## Estructura

```
index.html        contenido de la página
css/styles.css    estilos
fonts/            tipografías (Syne, Figtree y Caveat) en formato woff2
img/              retrato y capturas de los proyectos
favicon.svg       ícono de la pestaña
```

## Cómo editarlo

- Textos y enlaces: `index.html`. Cada proyecto es un bloque `<article class="project">`.
- Colores y tipografías: variables al inicio de `css/styles.css`.
- Para agregar un proyecto, copia un bloque `<article>` completo, cambia el contenido y sube su captura a `img/` (proporción 3:2).

## Publicación

1. Crea un repositorio público llamado `rusmericar.github.io`.
2. Sube todos los archivos de esta carpeta a la rama `main`.
3. En Settings, Pages, elige la rama `main` y la carpeta raíz.
