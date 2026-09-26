# Juju's Family — Link Hub

Página de enlaces para Juju, streamer, con acceso rápido a todas sus redes desde un solo lugar. Pensada para verse bien en celular, tablet y desktop.

**Demo:** abrí [`index.html`](index.html) en el navegador.

## Estructura del proyecto

```
juju/
├── index.html        Página principal (estructura y contenido)
├── css/
│   └── styles.css    Hoja de estilos: colores, tipografía y layout
├── img/
│   ├── avatar.jpg     Foto de perfil
│   └── favicon.webp   Ícono de la pestaña del navegador
└── README.md          Este documento
```

## Redes incluidas

- TikTok — [@julieta_iri](https://www.tiktok.com/@julieta_iri)
- Instagram — [@julii_iribarrenok](https://www.instagram.com/julii_iribarrenok)
- Discord — [Unirse al server](https://discord.gg/yEc2sjxwA)
- Steam — [Ver perfil](https://steamcommunity.com/profiles/76561199860279219)

## Diseño

- **Paleta:** violeta oscuro, magenta y rosa, con toques dorados. Fondo con degradé y resplandor sutil.
- **Tipografía:** [Baloo 2](https://fonts.google.com/specimen/Baloo+2) para títulos (cálida y redondeada) y [Nunito](https://fonts.google.com/specimen/Nunito) para el resto del texto.
- **Responsive:** la página se adapta a cualquier ancho de pantalla, desde celulares hasta monitores grandes.

## Cómo actualizar

### Cambiar textos (nombre, bio, enlaces)
Editá directamente `index.html`: buscá la sección `<div class="identity">` para el nombre y la bio, y `<nav class="links">` para los botones de redes.

### Cambiar colores o tipografía
Editá `css/styles.css`. Los colores principales están definidos como variables al principio del archivo (`--accent`, `--accent-2`, `--bg-0`, etc.), así que cambiándolas ahí se actualiza toda la página.

### Cambiar la foto de perfil
Reemplazá `img/avatar.jpg` por la nueva imagen manteniendo el mismo nombre de archivo (o actualizá la referencia `src="img/avatar.jpg"` dentro de `index.html`).

### Cambiar el ícono de la pestaña
Reemplazá `img/favicon.webp` por la nueva imagen (o actualizá la referencia en la etiqueta `<link rel="icon">`).

### Agregar una red nueva
Copiá uno de los bloques `<a class="link-btn ...">` dentro de `<nav class="links">`, cambiá el ícono, el color (`--tint`), el nombre y el enlace.

## Publicar el sitio (GitHub Pages)

1. Andá a **Settings → Pages** en el repositorio de GitHub.
2. En **Source**, elegí la rama `main` y la carpeta `/ (root)`.
3. Guardá los cambios. GitHub va a dar la URL pública en unos minutos (algo como `https://usuario.github.io/juju/`).

## Créditos

Desarrollado por [Vani](mailto:vaninasvilte@gmail.com) para Juju.
