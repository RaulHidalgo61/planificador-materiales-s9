# Planificador de materiales con kardex · ET505 S9

Proyecto individual basado en el planificador de Semana 7. Permite simular pedidos para afiches sobre el cuidado del agua y llevar el kardex de materiales ficticios.

## Aplicación publicada
- Repositorio: https://github.com/RaulHidalgo61/planificador-materiales-s9
- GitHub Pages: https://raulhidalgo61.github.io/planificador-materiales-s9/

## Archivos
- `index.html`: conserva el planificador S7 e integra la sección `#kardex` con IDs `k-*`.
- `styles.css`: conserva estilos S7 y añade etiqueta de 1.1rem y paleta azul `rgb(30,64,175)`.
- `app.js`: cálculo en céntimos, presupuesto S/ 180.00 y validación del pedido S7.
- `kardex.js`: materiales con IDs estables, búsqueda, cambio de nombre, movimientos, saldo, inactivación/eliminación, localStorage y exportación CSV.

## Uso y límites
Los saldos son unidades físicas y no cambian el presupuesto. Los datos son ficticios. `localStorage` pertenece al navegador y al origen actuales; no se comparte entre navegadores ni se sincroniza con una base común. El CSV es una copia descargable, no una sincronización con Excel.

## Comprobaciones documentadas
- Entrada 10 y salida 3: saldo 7.
- Salida 8 con saldo 7: rechazada, conserva saldo e historial.
- Cantidades 0, negativas y decimales: rechazadas.
- Búsqueda sin coincidencias, renombrado por ID, cancelación de eliminación e inactivación con historial: comprobados en Microsoft Edge.
- Recarga conserva movimientos; selección debe volver a elegirse.
- CSV abierto en Excel con ENTRADA 10 y SALIDA 3.
- Planificador: pedido de 4 × S/ 12.50 muestra total S/ 50.00 y saldo S/ 130.00. Los botones Comprobar y Confirmar rechazan un pedido de S/ 200.00 y conservan el último válido.

## Aportes y ayuda
Trabajo individual. Proyecto base: Semana 7; integración adaptada del recurso docente «Fragmentos de integración · ET505 · S9».
Ayuda recibida: OpenAI Codex, 29–30/10/2026. Se usó para revisar la consigna, mapear dependencias del fragmento, integrar el kardex y preparar pruebas/documentación. El estudiante adaptó el proyecto, publicó el sitio y ejecutó las comprobaciones descritas. Se corrigió el texto «Use al menos 3 caracteres» y se revisó la expectativa del encabezado CSV entrecomillado.
