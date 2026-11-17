# Mis pendientes

App de tareas con prioridad y dificultad. Se instala en el móvil y en el PC y sincroniza las tareas a través de un Gist privado de tu cuenta de GitHub.

## Publicarla (una sola vez)
1. Crea un repositorio nuevo en GitHub llamado `mis-pendientes` (público).
2. Sube todos estos archivos: «Add file» → «Upload files».
3. Ve a Settings → Pages → «Deploy from a branch» → rama `main`, carpeta `/ (root)` → Save.
4. Tras 1-2 minutos estará en `https://TU-USUARIO.github.io/mis-pendientes/`.

## Sincronizar
Pulsa el botón «Solo en este dispositivo · Conectar con GitHub», crea un token con permiso `gist` y pégalo. Usa el mismo token en cada dispositivo.

Archivos: index.html (la app), manifest.webmanifest y los iconos (para instalarla), sw.js (para que abra sin conexión).
