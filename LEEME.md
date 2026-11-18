# SeguridadBarrial — prototipo local

Primera versión funcional hecha con HTML, CSS y JavaScript. No requiere instalación.

## Abrir en VS Code
1. Descomprime `SeguridadBarrial.zip`.
2. En VS Code, selecciona **Archivo → Abrir carpeta…** y elige `SeguridadBarrial`.
3. Abre `index.html`. Si tienes la extensión Live Server, pulsa **Go Live**. También puedes abrir `index.html` con doble clic.

## Probar el flujo de alertas
1. En el menú, entra en **Alertas** y haz clic en cualquier reporte para ver su detalle.
2. Pulsa **Marcar como atendida**. El estado y el contador se actualizarán.
3. Puedes volver a abrir el detalle y pulsar **Reabrir reporte** para cambiarlo a “En revisión”.
4. En **Reportar incidente**, llena los campos y publica; luego busca el nuevo reporte en la lista.

Los reportes se almacenan solo en el navegador mediante `localStorage`; no se sincronizan con el computador de otra persona. Las alertas iniciales son de demostración. No uses el prototipo para emergencias reales ni escribas datos personales.

## Archivos
- `index.html`: pantallas y contenido.
- `styles.css`: diseño adaptable a computador y celular.
- `app.js`: navegación, formulario, búsquedas y estados de alerta.
