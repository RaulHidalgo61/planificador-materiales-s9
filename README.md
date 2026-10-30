# Planificador de materiales con kardex

## Propósito
Aplicación académica para planificar materiales para afiches sobre el cuidado del agua y registrar existencias físicas ficticias. No registra compras reales.

## Archivos
- `index.html`: conserva el planificador S7 y agrega la sección `#kardex` después del pedido; conserva los IDs `k-*` y evita formularios anidados.
- `styles.css`: conserva los estilos S7 y añade la personalización S9. La etiqueta usa 1.1rem en negrita y los botones usan azul RGB `rgb(30,64,175)`.
- `app.js`: conserva cálculo en céntimos, presupuesto S/ 180.00 y validación del planificador S7.
- `kardex.js`: gestiona materiales, búsqueda, renombrado por ID, entradas/salidas, saldo, inactivación/eliminación, localStorage y exportación CSV. Ejemplos: `MAT-001` y `MAT-002`.

## Uso y límites
Mantén los cinco archivos juntos y abre `index.html` en un navegador moderno. El saldo representa unidades físicas y es independiente del presupuesto monetario. Los datos viven sólo en el navegador y origen actuales; no se comparten. El CSV es una copia, no sincroniza Excel.

## Publicación
Repositorio GitHub: pendiente de crear.
GitHub Pages: pendiente de publicar y comprobar. Publica juntos los cinco archivos de este proyecto.

## Aportes y fuentes
Proyecto base: trabajo individual de Semana 7. Integración adaptada del recurso docente «Fragmentos de integración · ET505 · S9» (`kardex.html`, `kardex.js`, `personalizacion.css`, `MAPA_RECURSOS.md`, `LEEME.txt`).

Ayuda de IA: OpenAI Codex, 29/10/2026. Se consultó la consigna, la integración de los recursos S7/S9 y la rúbrica. Se aprovechó la revisión de dependencias, organización e integración inicial. El estudiante debe ejecutar las pruebas y documentar sus resultados reales en el PDF.

Publicación: [Configurar una fuente de publicación de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
