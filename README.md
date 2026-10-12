# App Dinero

App sencilla para anotar gastos e ingresos, ver cuánto te queda en el mes y poner presupuestos.
Funciona en el navegador y se puede instalar en el iPhone (Safari → Compartir → "Agregar a pantalla de inicio").

- Los datos se guardan solo en el teléfono (localStorage). En Ajustes puedes guardar una copia o exportar a Excel.
- Es una sola página: `index.html`. `sw.js` la guarda para que funcione sin internet.
- Para publicar una actualización: cambia los archivos y sube `VERSION` en `sw.js`.
