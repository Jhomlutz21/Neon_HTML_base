# AGENTS.md

## Contexto del proyecto
- Plantilla HTML de Cruip con Tailwind CLI.
- No hay framework; el build solo recompila `style.css` desde `css/style.css`.

## Objetivo de entorno (Windows + Git Bash + asdf)
- Todo el trabajo en Windows se realiza en Git Bash (no PowerShell) salvo indicacion.
- `asdf` es el manejador de versiones para Node.js y Yarn.
- Versiones objetivo: Node.js 24.6.0 y Yarn 1.22.22.

## Compatibilidad en Windows
- `asdf` no es nativo para Windows; se usa dentro de Git Bash.
- `asdf` debe inicializarse en `~/.bashrc` (definir `ASDF_DIR` y hacer `source` de `asdf.sh`).
- Usar rutas tipo `/c/Users/...` para evitar problemas con espacios.
- Si `asdf` falla en Windows, detenerse y pedir instrucciones antes de cambiar a otra alternativa.

## Flujo recomendado en Git Bash
- Verificar que `asdf` esta disponible (`asdf --version`).
- Asegurar plugins: `nodejs` y `yarn` (solo si faltan).
- Definir versiones locales con `.tool-versions` o `asdf local`.
- Ejecutar scripts con Yarn 1.x.

## Comandos habituales
- Instalar dependencias: `yarn install`
- Build CSS: `yarn run build`
- Desarrollo (watch): `yarn run dev`
