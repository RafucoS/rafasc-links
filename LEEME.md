# Página de enlaces (la del "Sitio web" de TikTok)

Hecha el 20-09-2026. Sustituye a Linktree: misma función, sin registrarte en otro sitio y con tu marca
(azul marino + lima, tu logo RSC, tipografías Archivo + IBM Plex).

## Qué contiene

1. **My UE5 materials on Fab** → https://www.fab.com/sellers/RafaSC
2. **Custom stylized 3D props** → https://www.fiverr.com/rafa_sc
3. **YouTube** → https://www.youtube.com/@RafaSC00

No lleva enlace a TikTok a propósito: quien abre esta página viene de ahí.
Tampoco lleva el botón de "Painted Edges gratis" porque tu ficha todavía no está publicada en Fab
(comprobado el 20-09: tu página de vendedor dice "RafaSC no ha publicado ningún recurso todavía").
En cuanto se publique, se añade arriba del todo como primer botón.

## Publicada y funcionando en

**https://rafucos.github.io/rafasc-links/**  (GitHub Pages, sin marcas de agua)

Repositorio: https://github.com/RafucoS/rafasc-links (rama `main`, carpeta raíz).
Para cambiar la página: editar `index.html`, `git commit` y `git push`; Pages se actualiza solo en 1-2 min.

### Copia anterior en Higgsfield (descartada)

https://rafasc-links.higgsfield.app — sigue en pie, pero lleva la insignia "Made in Higgsfield" que
inyecta su servidor y está listada en su feed de comunidad. No se usa.

Esa es la URL que se pega en TikTok → Editar perfil → Sitio web. Es pública: se abre sin cuenta,
sin iniciar sesión y desde el móvil. Alojada en el hosting de Higgsfield (Cloudflare Workers), con la
cuenta que ya estaba conectada.

Para que la URL fuese pública hubo que listar la página en el feed de la comunidad de Higgsfield:
https://higgsfield.ai/supercomputer/apps/30b05311-49bd-4bc3-bfb8-e48b0a6d27fc/view
Si no te gusta que aparezca ahí, se quita y la alojamos en otro sitio.

## Nota técnica

El `git push` fallaba con "could not read Username": el shell no tiene terminal (`/dev/tty`) y el Git
Credential Manager no podía preguntar. Se arregla forzando su ventana gráfica:
`GCM_GUI_PROMPT=1 GCM_INTERACTIVE=always git push`.

## Copia local

`index.html` es un archivo suelto, sin dependencias externas salvo las fuentes de Google (el logo va
dentro del propio archivo). Vale tal cual para GitHub Pages, Netlify Drop o cualquier hosting.

## Versión en Claude

https://claude.ai/artifact/MFibrodd3jwJ6JwE8PATyW — privada, solo la ves tú. Sirve de copia, no como
enlace público.
