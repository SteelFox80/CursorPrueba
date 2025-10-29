# PeluPaws — Landing minimalista (estático)

Sitio estático en HTML/CSS para promocionar el shampoo para perros PeluPaws. Listo para desplegar en Vercel.

## Estructura

- `index.html`: contenido principal de la landing
- `styles.css`: estilos con paleta pastel y diseño minimalista
- `assets/logo.svg`: logo simple del producto

## Despliegue en Vercel

1. Crea un repositorio (GitHub/GitLab/Bitbucket) y sube estos archivos.
2. Entra a Vercel y elige "New Project" → importa tu repositorio.
3. Ajustes de proyecto:
   - Framework: "Other" (sitio estático)
   - Build Command: vacío
   - Output Directory: `/` (raíz)
4. Deploy. Vercel servirá `index.html` por defecto.

## Personalización rápida

- Reemplaza `assets/logo.svg` con tu logo.
- Cambia colores pastel en `styles.css` (`:root`).
- Actualiza el correo del CTA `mailto:` en `index.html`.

## Licencia
Uso interno para POC.
