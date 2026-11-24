# AGENTia — Landing Page

Landing page estática de AGENTia (agentia-group.com).

## Archivos

- `index.html` — estructura y contenido.
- `styles.css` — diseño, responsive y animaciones.
- `assets/` — identidad gráfica (logo oficial de agentia-services.com):
  - `logo.png` — lockup completo (emblema + wordmark), fondo transparente; se usa en el header.
  - `logo-emblem.png` — solo el emblema (círculo con los tres arcos y núcleo).
  - `logo-wordmark.png` — solo el texto "AGENTia / INTELLIGENT SERVICES".
  - `favicon-16.png`, `favicon-32.png`, `favicon-48.png`, `apple-touch-icon.png` (180×180) — emblema.
  - `og-image.png` (1200×630) — imagen para redes; su plantilla editable es `og-image.html`.

## Ejecutar localmente

No requiere Node ni dependencias.

1. Abre la carpeta en VS Code.
2. Abre `index.html` en un navegador.

Para una experiencia más cómoda puedes usar la extensión **Live Server** de VS Code.

## Publicar

La página es estática y puede publicarse en GitHub Pages, Vercel, Netlify o cualquier hosting estático.

### GitHub Pages

Este proyecto está configurado para publicarse desde:

`ceasarm7/AgentIA`

En GitHub:

**Settings → Pages → Deploy from branch → `main` → `/ (root)`**

## Datos actuales

- Web: https://agentia-group.com
- Email: contacto@agentia-group.com
- Teléfono: +52 33 1848 0673
- Ubicación: Guadalajara, México

## Oferta: Agentia en Servidor NVIDIA Privado (sección `#servidor`)

- Instalación y entrenamiento de Agentia sobre el servidor NVIDIA privado del cliente: **USD 999** (pago único).
- Mensual por usuario (el precio baja al sumar usuarios):
  - 1er usuario: **USD 419/mes**
  - 2do usuario: **USD 299/mes**
  - Usuarios 3 a 5: **USD 199/mes c/u**
  - Usuarios 6 a 10: **USD 99/mes c/u**
- Incluido por usuario y mes: 1 hora de soporte + actualizaciones de Agentia + parches de seguridad.
- Desarrollo específico y soporte adicional: suplemento bajo demanda (se cotiza).
- Argumento ROI: el servidor es retorno de inversión — Agentia-max (nuestro propio modelo) procesa 120M+ tokens/día y 3000M+ tokens/mes.

## Carta gráfica

Identidad visual de AGENTia para la web (logo oficial tomado de agentia-services.com).

- **Emblema**: círculo navy `#171E26` con tres arcos orbitales de gradiente — coral `#FD605B`, violeta `#CB6DE5` e índigo `#6F6EE6` — girando alrededor de un núcleo blanco luminoso (motivo de "agente en órbita / inteligencia central").
- **Wordmark**: "AGENT**ia**" en negrita — la "i" en coral `#FD605B` y la "a" en azul claro `#7FB2FF` — con "INTELLIGENT SERVICES" en capitales espaciadas debajo.
  - Fondo claro: "AGENT" en ink `#0d1025`, subtítulo `#667085`.
  - Fondo oscuro: "AGENT" en blanco, subtítulo `#8d99b0`.
- **Colores base** (tokens en `styles.css`):
  - Navy `#050b20` · Blue `#2864ff` · Violet `#7138ee` · Purple `#a22cff` · Cyan `#28c8ff`
  - Soft `#f7f8fc` · Ink `#0b1633` · Muted `#667085` · Line `#e8ebf3`
- **Tipografía**: Inter (Google Fonts), pesos 400–800.
- **Uso del logo**:
  - Header (fondo claro) → `assets/logo.png` (lockup completo, altura 46px).
  - Footer (fondo oscuro) → `assets/logo-emblem.png` + texto "AGENTia" con acentos coral/azul.
  - No redibujar ni recolorear el emblema; se usa tal cual (PNG transparente).
- **Favicon**: emblema en PNG 16/32/48 y apple-touch 180.
- **OG image**: `assets/og-image.png` 1200×630, navy con glows blue/violet/coral, emblema como marca de agua a la derecha y chips de estadísticas.
- **Fuente del logo**: `https://agentia-services.com/logo.png` (674×370) y `favicon.png` (158×148). Si la carpeta de Drive con los archivos fuente (vectores) se hace pública, se regenera el set en alta resolución.
