# Módulo 8 - Cloud: Render (despliegue manual)

App Vite + React + TypeScript desplegada en Render como Static Site con despliegue manual.

## Enlace

- **App desplegada:** https://modulo08-cloud-render.onrender.com

## Cómo se despliega

El repositorio está conectado a un Static Site de Render con esta configuración:

- **Build Command:** `npm ci && npm run build`
- **Publish Directory:** `dist`
- **Auto-Deploy:** desactivado

Render hace el build en sus servidores, pero solo cuando se lanza a mano desde el dashboard (Manual Deploy → Deploy latest commit). Un push a `main` no actualiza la web por sí solo.