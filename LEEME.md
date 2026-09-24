# TIKISSHOP — Tienda online de fundas para iPhone

Código fuente completo de la página web de TIKISSHOP, lista para correr localmente.

## Requisitos

- Node.js 20+ o Bun instalado

## Cómo ejecutar

```bash
# Con Bun (recomendado, usa el bun.lock incluido)
bun install
bun run dev

# Con npm
npm install
npm run dev
```

Luego abrí http://localhost:8080 en el navegador.

## Estructura principal

- `src/routes/index.tsx` — Página completa (Header, Hero, Catálogo, Nosotros, Redes, Contacto, Footer)
- `src/styles.css` — Tokens de color (azul marino + dorado), fuentes Manrope/Space Grotesk, animaciones
- `src/components/ui/button.tsx` — Botones con variantes gold y heroOutline
- `src/assets/` — Imágenes reales de catálogo (iPhone 11–16) e imagen del hero
- `public/favicon.svg` — Favicon de la marca

## Datos de la marca

- WhatsApp: 096 130 882 (https://wa.me/59896130882)
- Instagram/TikTok: @TIKISSHOPP
- Email: FEDERODRIGUEZZ1224@GMAIL.COM

## Editar el catálogo

En `src/routes/index.tsx`, el array `products` define cada tarjeta. Para agregar un modelo nuevo, copiá una línea y cambiá el nombre, modelo e imagen:

```js
{ id: 7, name: "Silicona iPhone 17", model: "iPhone 17 · 17 Pro · 17 Pro Max", group: "iPhone 17", image: catalog17, badge: "Nuevo" },
```

## Notas

- Las fundas son de silicona con interior en microfibra.
- Los precios no se muestran: cada botón abre WhatsApp con un mensaje prellenado para consultar.
- Stack: TanStack Start + React 19 + Vite + Tailwind CSS v4.

© 2026 TIKISSHOP. Uruguay 🇺🇾
