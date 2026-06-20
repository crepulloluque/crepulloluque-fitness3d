# Entrena en Casa 3D

Sitio estático (HTML/CSS/JS) de rutinas y técnica de ejercicio en casa, con
diagramas tipo "blueprint" que conectan con el proyecto Workout3D.

## Estructura

```
index.html              → página de inicio
style.css                → sistema de diseño completo
script.js                → menú móvil + animaciones al hacer scroll
articulos/
  sentadilla-tecnica.html → primer artículo (plantilla a replicar)
```

## Cómo publicarlo en GitHub Pages (gratis)

1. Sube estos archivos al repositorio `crepulloluque-fitness3d`
   (puedes arrastrarlos directamente desde la web de GitHub, en
   "Add file → Upload files", o por git si lo prefieres).
2. Ve a **Settings → Pages** del repositorio.
3. En "Source", selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos minutos tu sitio estará en:
   `https://crepulloluque.github.io/crepulloluque-fitness3d/`

## Cómo añadir un nuevo artículo

1. Duplica `articulos/sentadilla-tecnica.html`.
2. Cambia el `<title>`, `<meta description>`, el `<h1>` y el contenido.
3. Añade una nueva tarjeta `<a class="card">` en `index.html` apuntando
   al nuevo archivo.

## Antes de solicitar AdSense

- Ten publicados al menos 15-20 artículos con contenido propio y útil.
- Revisa que cada página tenga `title` y `meta description` únicos (ya
  preparado en la plantilla).
- Cuando tengas la cuenta aprobada, descomenta la línea de AdSense en el
  `<head>` de `index.html` y sustituye `ca-pub-XXXXXXXXXXXXXXXX` por tu ID
  real. Los `<div class="ad-slot">` marcan dónde colocar los bloques de
  anuncio.
