# Ayudantías · Introducción a la Ciencia de Datos

Material de ayudantía en formato de páginas web interactivas. Cada ayudantía es un único archivo HTML autocontenido: no requiere instalar nada y funciona sin conexión (salvo la tipografía matemática KaTeX, que se carga desde un CDN).

| | Tema |
|---|---|
| [Ayudantía 1](ayudantia_1.html) | Webscraping y APIs |
| [Ayudantía 2](ayudantia_2.html) | Análisis exploratorio y regresión lineal (datos PAES 2026, DEMRE) |

## Ver el sitio

Publicado con GitHub Pages desde la rama `main` (carpeta raíz). La portada es `index.html`.

Para verlo localmente, basta con abrir `index.html` en el navegador.

## Estructura

```
index.html          portada con enlaces a cada ayudantía
ayudantia_1.html    Webscraping y APIs
ayudantia_2.html    EDA y regresión lineal
.nojekyll           le indica a GitHub Pages que sirva los archivos tal cual
```

## Agregar una ayudantía nueva

1. Crear `ayudantia_N.html`.
2. Agregar su tarjeta en `index.html`.
3. Agregar los botones de navegación (⌂ Inicio / anterior / siguiente) en el encabezado de la ayudantía anterior y de la nueva.

## Fuentes de datos

- Ayudantía 2: bases públicas del Proceso de Admisión 2026, [DEMRE](https://demre.cl/), Universidad de Chile. Los widgets usan agregados y una muestra de 2.000 casos incrustados en la página; los CSV originales no se incluyen en el repositorio.
