# LemoncodeLab1

Laboratorio Módulo 1 Lemoncode: landing con Vite + Tailwind v4

## Tema elegido

_Pendiente._

## Cómo arrancarlo

```bash
npm install
npm run dev
```

Abre la URL que muestra Vite en la terminal (por defecto, http://localhost:5173).

## Cómo conecto Tailwind

Elijo la **opción 1: el plugin de Vite** (`@tailwindcss/vite`).

Elijo el plugin de Vite porque es la integración nativa y recomendada para Vite: menos configuración y dependencias, y compilación más rápida. PostCSS tendría sentido si necesitara otros plugins de PostCSS o una herramienta sin plugin propio.

- Configuración: `vite.config.js` con `plugins: [tailwindcss()]`.
- Hoja de estilos: `src/style.css` con `@import "tailwindcss";`, enlazada desde `index.html` con un `<link>` (el proyecto no usa JavaScript).

## Capturas

### Móvil

_Pendiente._

### Escritorio

_Pendiente._

## Checklist

### Obligatorios

- [ ] O1 · Estructura semántica
- [ ] O2 · Tema visual con `@theme`
- [ ] O3 · Cabecera con flexbox
- [ ] O4 · Hero
- [ ] O5 · Rejilla de tarjetas con grid
- [ ] O6 · Pasos o destacados con flexbox
- [ ] O7 · Pie de página
- [ ] O8 · Accesibilidad mínima (Lighthouse · Accesibilidad: _pendiente_)
- [ ] O9 · README + bitácora de IA

### Opcionales

_Pendiente._

### Desafíos

_Pendiente._

## 🤖 Bitácora de IA

**Herramienta:** Claude Code (extensión de VS Code).

_Pendiente: al menos 3 ejemplos._
