# PRISMA V0.7

Prototipo funcional de PRISMA para Formulación Inorgánica.

## Cambios de esta versión
- En preguntas **fórmula → nombre**, PRISMA muestra siempre **dos nomenclaturas válidas** después de responder.
- Se aceptan ambas nomenclaturas como respuesta correcta, además de variantes de escritura como `óxido de plomo IV`, `óxido de plomo(IV)` y `óxido de plomo (IV)`.
- Se amplía el banco de **100 a 140 actividades**.
- Se incorporan **ácidos**: hidrácidos y oxoácidos.
- Se incorporan **sales**: binarias, oxisales y sales con hidrógeno.
- Se mantiene el análisis del error tras un fallo, comparando la respuesta del alumno con las soluciones válidas.
- El progreso de las versiones anteriores no se reutiliza: esta versión usa una nueva clave de almacenamiento local.

## Estructura actual
- CASO 01 — Óxidos
- CASO 02 — Hidruros
- CASO 03 — Hidróxidos
- CASO 04 — Ácidos
- CASO 05 — Sales
- CASO 06 — Ácidos
- CASO 07 — Sales

Cada CASO contiene 20 preguntas. Al volver a entrar en un CASO se inicia un nuevo intento de 20 preguntas y la pantalla de módulos conserva el resumen del último intento.

## Uso
Abre `index.html` en un navegador moderno.

No requiere servidor ni instalación.
