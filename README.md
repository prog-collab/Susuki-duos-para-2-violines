# Fun for 2 Violins — índice interactivo

Aplicación web (una sola página) para localizar y abrir cada pieza de los tres
volúmenes de *Fun for 2 Violins* (dúos para dos violines, repertorio Suzuki,
arreglos de Marianne Rygner). Cada canción es un PDF independiente en `canciones/`.

## Uso
Abre `index.html`. Busca por título, compositor o país, cambia la interfaz
entre **ES/EN** y pulsa una pieza para abrir su PDF.

## Instalar como app (Chrome / Edge)
La página es una PWA. Al servirla por HTTPS (p. ej. GitHub Pages), el navegador
muestra el icono **Instalar** en la barra de direcciones; también desde
menú ⋮ → *Instalar Fun for 2 Violins*. Una vez instalada funciona sin conexión.


## Visor con pase de página por pedal
Cada pieza se abre en `viewer.html`: muestra **una página a la vez a pantalla
completa** y se pasa **de lado**. Funciona con pedales para partituras
(AirTurn, PageFlip, etc.) y con teclado:

- **Siguiente:** flecha derecha/abajo, Re Pág, barra espaciadora o Enter
- **Anterior:** flecha izquierda/arriba, Av Pág o Retroceso
- También: clic en los bordes, deslizar el dedo, botones en pantalla, **F** pantalla completa

> Configura tu pedal en modo "teclas de flecha" o "Page Up/Down".

## Publicar en GitHub Pages
1. Sube todo el contenido de esta carpeta a un repositorio.
2. *Settings → Pages → Branch: main / root*.
3. Abre la URL que te da GitHub (HTTPS).

## Contenido
- `index.html` — índice bilingüe con buscador
- `canciones/` — 34 PDF (18 + 8 + 8)
- `manifest.webmanifest`, `sw.js`, `icon-*.png` — soporte PWA
