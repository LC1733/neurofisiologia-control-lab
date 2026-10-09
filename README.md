# Neurophysiology Control Lab

Simulador educativo, en un solo archivo HTML sin dependencias, de la respuesta autonómica (SAM), el eje HPA y la experiencia subjetiva en una línea de tiempo de 60 minutos, con **comparador A/B lado a lado** contra un estado de reposo de referencia.

**No es un instrumento clínico.** Los valores los genera un modelo didáctico; no miden a ninguna persona ni diagnostican nada. La banda de referencia (±10 % del rango de escala) es una convención de la app, no un rango clínico.

- Sitio: https://lc1733.github.io/neurofisiologia-control-lab/
- Forma parte del hub **Mente & Decisión**: https://lc1733.github.io/
- `catalog.json` describe la app para el hub (convención nivel B: el hub lo lee y sobrescribe su entrada central).

## Versiones
- **1.2** — monitor ECG sintético A/B en tiempo real (reloj del navegador, independiente de FPS; RR con oscilación respiratoria según tono vagal; QT con corrección de Bazett), mapa de órganos diana A/B con dirección del efecto (simpático, vagal, cortisol) y su base fisiológica, estado activo/en reposo/atenuado en las vías SAM y HPA. Incorpora las piezas útiles de la consola "SYS_NEURO" sin sus valores absolutos de cortisol.
- **1.1** — comparador A/B con dos gráficos sincronizados, traza de reposo y banda de referencia, tabla de índices (pico, t pico, retorno, carga), privación de sueño como modificador, rangos poblacionales de FC/PA/respiración en el detalle de cada tarjeta, corrección del eje Y en "Órganos", tarjetas sin re-render por tick.
- **1.0** — versión inicial.
