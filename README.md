# Portafolio — Victoria Isabel Lemus

Sitio personal que reúne las dos mitades del trabajo: las campañas de marketing digital
que dejaron números y los productos que salieron de esos números.

Publicado en GitHub Pages: https://vickybel.github.io

## Estructura

```
index.html          Portada única: desarrollo, casos de marketing, método y contacto
obras/              Una hoja de diseño por proyecto
  almacigo.html       App de crianza compartida (Expo · Supabase)
  novelas.html        Plataforma de lectura por suscripción (Next.js · Supabase)
  daelead.html        Landing de SaaS de inteligencia comercial (HTML · Netlify Forms)
  victoriaisabel.html Sitio de consultoría propio (Astro · Netlify)
.nojekyll           Sirve los archivos tal cual, sin procesarlos con Jekyll
```

Cada hoja de `obras/` dibuja el flujo del proyecto y sus pantallas en HTML y CSS,
usando la paleta y las tipografías de cada repositorio.

## Cómo verlo en local

No hay build ni dependencias. Abre `index.html` en el navegador, o levanta un servidor:

```bash
python3 -m http.server 4321
```

Y entra a http://localhost:4321

## Notas técnicas

- Sin frameworks ni empaquetador. HTML y CSS a mano; el único JavaScript son los
  destellos del fondo y el desplazamiento del menú.
- Tema claro y oscuro por tokens CSS, siguiendo la preferencia del sistema.
- Toda animación se apaga con `prefers-reduced-motion: reduce`.
- Tipografías desde Google Fonts: Fraunces (titulares) y Manrope (interfaz, la misma
  de victoriaisabel.cl).
