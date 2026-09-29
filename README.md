# CAMPAR SGC Digital v0.3

Versión preparada para exposición preliminar a Dirección y simulación de una prueba piloto digital.

## Novedades de v0.3
- Flujo operativo conectado: OC → Producción → Inspección → Inventario / NC → Entrega.
- Persistencia local mediante `localStorage`: la demo conserva cambios al recargar el navegador.
- Creación real de OC dentro del prototipo.
- Asignación de producción vinculada a la OC.
- Actualización de avance de producción y transición automática a “Pendiente inspección”.
- Muestreo automático según tamaño de lote para el esquema piloto.
- Inspección con dos escenarios de demostración: conforme o con NC.
- Liberación restringida visualmente a Gustavo / Alessandri.
- Una liberación actualiza inventario automáticamente.
- Una inspección retenida genera una NC vinculada y producto retenido.
- Retrabajo puede regresar el lote a reinspección.
- Entregas se crean desde inventario disponible y actualizan existencias.
- Trazabilidad por OC entre asignaciones, inspecciones, NC y entregas.
- Vista Dirección y modo de demostración.
- Botón para restablecer los datos demo.

## Publicación en GitHub Pages
Sube **el contenido de esta carpeta** a la raíz del repositorio:

- `index.html`
- `styles.css`
- `app.js`
- `assets/`
- `docs/`

Después: **Settings → Pages → Deploy from a branch → main → /(root)**.

## Importante
Esta versión sigue sin backend y no constituye el sistema productivo definitivo. Los datos se guardan únicamente en el navegador donde se ejecuta la demo. Los documentos del SGC permanecen EN REVISIÓN hasta aprobación formal de CAMPAR.
