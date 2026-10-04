# 🌱 Mi Primera Huerta

Aplicación web interactiva de una sola página (SPA) para guiar a un principiante en la creación de su primer huerto familiar orgánico, basada en la estructura y contenidos del **Manual técnico: El huerto familiar orgánico y nutritivo** (PMA/MAGAP Ecuador).

## Demo

https://martnmartnez14.github.io/mi-primera-huerta/

## Características

- **SPA de 6 vistas** sin recargar: Inicio, Ecosistema, Suelo, Hortalizas, Diseño y Nutrición.
- **Grafo de conexiones** en SVG con resaltado de relaciones y panel lateral explicativo.
- **Capas del suelo** interactivas (horizontes O, A, B y C) con modal detallado.
- **Catálogo de 17 hortalizas** de las 8 clases (raíz, tubérculo, bulbo, hoja, fruta, tallo, flor y leguminosa) + aromáticas.
- **Planificador drag & drop** sobre una cuadrícula 6×6, con validación de plantas compañeras y enemigas.
- **Radar chart de nutrientes** en SVG nativo (Vitamina A, Vitamina C, Hierro, Calcio y Fibra).
- **Modo Novato / Experto** con persistencia en `localStorage`.

## Uso

Abre `index.html` directamente en tu navegador. No requiere instalación ni servidor.

## Tecnología

HTML5 + CSS3 + JavaScript (ES6+) en un único archivo, sin frameworks ni dependencias externas (salvo Google Fonts, con fallback a `system-ui`).

## Estructura

- `index.html` — la aplicación (copia para GitHub Pages).
- `mi-primera-huerta.html` — archivo original.

## Créditos

Contenido basado en el manual del PMA/MAGAP Ecuador (2012). Proyecto educativo.
