# IGNITE — Enciende ideas

Sitio web de IGNITE, diseño y construcción eléctrica en Guayaquil, Ecuador.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `ignite-web`).
2. Sube todo el contenido de esta carpeta: `index.html` y la carpeta `assets`.
3. En el repositorio, entra a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`. Guarda.
5. En uno o dos minutos el sitio queda en `https://TU-USUARIO.github.io/ignite-web/`.

Si el repositorio se llama `TU-USUARIO.github.io`, el sitio queda directamente en `https://TU-USUARIO.github.io/`.

## Estructura

```
index.html                 Página completa (incluye el plano y el logo en vector)
assets/js/                 GSAP, ScrollTrigger y Lenis (animaciones y scroll suave)
assets/fonts/              Tipografías Anton y Jost
```

## Probar en tu computadora

Las tipografías no cargan si abres `index.html` con doble clic. Usa un servidor local:

```
python -m http.server
```

y abre `http://localhost:8000`.

## Editar datos de contacto

Busca en `index.html` el número `593967879169`, el correo `Ignite.ec@outlook.com` y `ignite_ec` para cambiarlos.
