# AGENTS.md

## Contexto del proyecto
- Plantilla HTML de Cruip con Tailwind CLI.
- No hay framework; el build solo recompila `style.css` desde `css/style.css`.

## Entorno esperado
- Windows 10 Pro.
- Node.js 24.6.0.
- Yarn 1.22.22.
- Git Bash disponible; `asdf` es opcional si ya esta instalado.

## Reglas para el agente
- Revisar archivos clave (por ejemplo `package.json`, `README.md`) y proponer un plan breve antes de ejecutar comandos que modifiquen el repo.
- Usar Yarn 1.x para scripts y dependencias; evitar npm/pnpm salvo que se solicite.
- Mantener los lockfiles existentes; no eliminarlos ni reemplazarlos sin pedirlo.
- Si hay dudas sobre el entorno, los comandos o la idea del feature/task preguntar antes de proceder.

## Comandos habituales
- Instalar dependencias: `yarn install`
- Build CSS: `yarn run build`
- Desarrollo (watch): `yarn run dev`
