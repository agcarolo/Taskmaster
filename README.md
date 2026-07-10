# Fichaje

Tracker personal de tareas y tiempo. Web estática (un solo `index.html`), sin dependencias ni build.

## Qué hace
- Fichaje de tareas con cronómetro: Empezar / Pausar / Reanudar / Terminar
- Estados: Pendiente · En curso · Pausada · Terminada
- Proyectos con tiempo acumulado
- Totales por Hoy / Semana / Mes / Todo, por categoría o proyecto
- Categorías personalizables
- Export a Excel (.xlsx): hojas Tareas, Sesiones y Proyectos

## Datos
Se guardan en `localStorage` del navegador (por dispositivo). El export a Excel sirve de copia de seguridad.

## Publicar con GitHub Pages
1. Sube este repo a GitHub
2. Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save
3. En ~1 minuto: `https://<usuario>.github.io/fichaje/`

## Desarrollo local
Abrir `index.html` en el navegador. Ya está.
