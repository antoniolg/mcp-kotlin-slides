# MCP Kotlin Slides

Presentación sobre el SDK de Model Context Protocol (MCP) para Kotlin y casos prácticos.

## Requisitos

- Node.js 18+ (recomendado usar la versión LTS actual)
- npm 9+

## Cómo ejecutar las slides

1. Instala dependencias:
   ```bash
   npm install
   ```
2. Lanza el servidor de desarrollo de Slidev:
   ```bash
   npm run dev
   ```
3. Abre el enlace que muestra la consola (por defecto `http://localhost:3030`).

## Generar la versión estática

Para exportar las slides a HTML estático:
```bash
npm run build
```
Los archivos quedarán en `dist/`.

## PDF opcional

Slidev permite generar un PDF si tienes instalado [Playwright](https://playwright.dev/):
```bash
npm run export
```
Esto produce `slides-export.pdf`.

## Estructura

- `slides.md`: contenido principal de la charla.
- `assets/`: imágenes usadas en las slides.
- `vite.config.js`: configuración adicional de Slidev/Vite.

## Créditos

Slides preparadas por Antonio López González (antoniolg).
