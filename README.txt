# deleFOCO — Location Landing

## Archivos
- `index.html` — landing completa de Locaciones.
- `styles.css` — diseño responsive, temas claro/oscuro, accesibilidad y estados visuales.
- `script.js` — cambio ES/EN, cambio Empresas/Particulares, filtros de catálogo, modal, formulario hacia WhatsApp y tema claro/oscuro.

## Ejecutar
No requiere Node ni instalación:
1. Abrí `index.html` en Chrome, Edge, Firefox o Safari.
2. La página funciona directamente en el navegador.

## Funcionalidades
- Selector de audiencia: Empresas / Particulares.
- Selector de idioma: ES / EN.
- Tema claro / oscuro.
- Filtros de catálogo: Natural, Urbano, Interior, Industrial e Histórico.
- Modal para consultar cada referencia de locación.
- Formulario con validación HTML y generación de solicitud para WhatsApp.
- Diseño responsive para escritorio, tablet y móvil.
- Estados accesibles con `focus-visible`, `aria-live`, etiquetas ARIA y soporte para `prefers-reduced-motion`.

## Imágenes
Las tarjetas del catálogo utilizan imágenes remotas alojadas en `delefoco.com`. Para una entrega definitiva, verificá que esas imágenes tengan autorización de uso y que sus URLs permanezcan públicas. Si la entrega debe funcionar sin conexión, descargá las imágenes autorizadas y reemplazá las URLs remotas por archivos locales.

## Nota
La página implementa la landing de Locaciones y no el resto de módulos del ecosistema deleFOCO. Los enlaces del footer que pertenecen a otros módulos apuntan al sitio principal para evitar enlaces internos inexistentes dentro de esta landing.
