# AgentIA Group — Landing Page

Landing page estática de AgentIA Group.

## Archivos

- `index.html` — estructura y contenido.
- `styles.css` — diseño, responsive y animaciones.
- `favicon.svg` — favicon vectorial (marca sobre tile navy).
- `assets/` — gráfico de marca:
  - `logo-mark.svg` — solo la marca (fondo transparente).
  - `logo-full.svg` / `logo-full-white.svg` — lockup horizontal (fondo claro / oscuro).
  - `favicon-16.png`, `favicon-32.png`, `favicon-48.png`, `apple-touch-icon.png` (180×180).
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

Identidad visual de AgentIA Group para la web.

- **Marca**: un "A" formado por dos trazos con ápice redondeado y un nodo circular en la pierna izquierda (motivo de "nodo/agente").
- **Gradiente de marca**: diagonal de abajo-izquierda a arriba-derecha, `#2864ff → #5331e8 → #a22cff`.
- **Colores base** (tokens en `styles.css`):
  - Navy `#050b20` · Blue `#2864ff` · Violet `#7138ee` · Purple `#a22cff` · Cyan `#28c8ff`
  - Soft `#f7f8fc` · Ink `#0b1633` · Muted `#667085` · Line `#e8ebf3`
- **Tipografía**: Inter (Google Fonts), pesos 400–800.
- **Uso del logo**:
  - Fondo claro → `assets/logo-full.svg` (texto ink `#0b1633`).
  - Fondo oscuro → `assets/logo-full-white.svg` (texto blanco).
  - Solo la marca → `assets/logo-mark.svg`.
  - El gradiente de la marca no se altera; el texto "IA" usa el gradiente `#2864ff → #8a32f3`.
- **Favicon**: `favicon.svg` (tile navy `#050b20`, radio 14/64) + PNG 16/32/48 y apple-touch 180.
- **OG image**: `assets/og-image.png` 1200×630, navy con glows blue/violet, marca de agua de la marca a la derecha y chips de estadísticas.
