# LemoncodeLab1

Laboratorio Módulo 1 Lemoncode: landing con Vite + Tailwind v4

## Cómo conecto Tailwind

Elijo la **opción 1: el plugin de Vite** (`@tailwindcss/vite`).

Elijo el plugin de Vite porque es la integración nativa y recomendada para Vite: menos configuración y dependencias, y compilación más rápida. PostCSS tendría sentido si necesitara otros plugins de PostCSS o una herramienta sin plugin propio.

- Configuración: `vite.config.js` con `plugins: [tailwindcss()]`.
- Hoja de estilos: `src/style.css` con `@import "tailwindcss";`, enlazada desde `index.html` con un `<link>` (el proyecto no usa JavaScript).
