# Mis IPTV

Web para tener organizadas las IPTV: usuario, contraseña y enlace M3U de cada amigo, con añadir, editar, borrar y copiar.

- Página estática servida con GitHub Pages (`index.html`).
- Los datos se guardan en Supabase (tabla `iptvs`) con Row Level Security: cada cuenta solo puede leer y modificar sus propias filas.
- La clave que aparece en `index.html` es la clave pública (publishable) de Supabase; es segura en el navegador.
