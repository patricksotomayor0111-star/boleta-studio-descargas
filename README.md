# Boleta Studio 0.10

**[Descargar actualización 0.10 para Android](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.10.apk)**

[Descargar el mismo APK en ZIP](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.10.zip)

Esta versión mejora las filas de productos, la línea inferior, el tamaño de letra, el formato del resumen, la fecha del PDF y los cálculos de IGV, pago y vuelto. Conserva las plantillas y el editor de la versión anterior.

## Instalar como actualización

1. Abre el enlace del APK en Chrome desde tu celular y acepta la descarga.
2. En Chrome, abre **⋮ → Descargas** y toca `Boleta-Studio-0.10.apk`.
3. Si Android solicita permiso para instalar desde Chrome, concédelo y vuelve al instalador.
4. Pulsa **Actualizar**. Conserva instalada la aplicación anterior para mantener tus datos.

Android ARM64, Android 6 o posterior, mismo paquete y firma que las versiones anteriores. El ZIP contiene el mismo APK y debe extraerse primero. Los avisos automáticos dentro de la app siguen pendientes.

## Productos encima de la línea

La línea final acompaña al último producto y los totales bajan junto con la tabla. Las filas reservan espacio para los textos y los valores movidos. Al abrir un diseño anterior se corrige el anclaje de la línea inferior cuando se reconoce dentro del grupo de productos. Los elementos siguen siendo movibles y admiten **Deshacer**.

Los productos nuevos calculan su importe por defecto y actualizan la suma, incluso si los importes anteriores se conservaron del escaneo. En ese modo, se mantienen los importes de las otras filas. También se actualiza la suma al eliminar un producto.

En **Diseño → Letra de todos los productos**, elige el tamaño común, por ejemplo **19**. Las descripciones, cantidades e importes lo comparten y los productos nuevos lo heredan. Si ya habías corregido individualmente la letra de las descripciones, se toma ese ajuste al preparar el diseño anterior. Al editar un texto de producto también está **Aplicar tamaño a todos los productos**; puedes desactivarlo para un ajuste individual.

## Resumen como párrafo

1. En **2. Vista previa**, toca el texto del resumen o pie.
2. En **Alineación**, elige **Izquierda, Centro, Derecha o Justificado**.
3. **Ajustar párrafo al ancho** reacomoda los renglones del escaneo dentro del cuadro y conserva los párrafos separados por una línea vacía y las viñetas. Desactívalo para mantener tus saltos de línea escritos.
4. Pulsa **Aplicar** y después **Guardar** para conservar la plantilla.

## Fecha y hora del PDF

En **Editar datos → Datos de la operación** está **Fecha y hora actuales al guardar PDF**, activada por defecto. Al terminar de elegir dónde guardar el PDF, se usa la hora local del teléfono y se actualiza también la vista previa.

El PDF conserva esa misma fecha cuando lo vuelves a abrir. Cambiar manualmente el campo de fecha desactiva la opción automática; puedes volver a activarla.

El PDF conserva sin pérdida el dibujo limpio de la vista previa, sin los controles del editor. Los textos mantienen sus posiciones y tamaños al abrir el archivo. Para editar el contenido, vuelve a la app y guarda nuevamente el PDF.

## IGV, pago y vuelto

- En **Importes**, activa el cálculo automático para actualizar cantidades, precios, descuentos, subtotal, IGV y total.
- **Los precios incluyen IGV** obtiene la base y el impuesto desde el total. Desactívalo si corresponde añadir el IGV; se añade una sola vez.
- En **Pago y vuelto**, escribe **Pagó con**. Se actualiza el vuelto y, si el pago no alcanza, se indica cuánto falta y el vuelto queda en cero.
- Un pago vacío conserva el vuelto importado. También puedes desactivar el vuelto automático.
- **Diseño** permite mostrar u ocultar **Pagó con**, y añadir el subtotal e IGV calculados cuando el diseño por campos no los incluía. Calcular IGV no obliga a añadir esas líneas visualmente.

Ejemplo comprobado: productos por **S/ 15.10**, IGV incluido al 18 %, subtotal **S/ 12.80**, IGV **S/ 2.30**, pago **S/ 20.00** y vuelto **S/ 4.90**.

## Columnas según cada foto

Se mantienen las mejoras de 0.9: una importación completa reconoce los títulos, el orden y el espacio de las columnas de esa foto. **Plantillas → Ajustar distribución a la foto** permite corregir la distribución de una boleta ya guardada conservando sus precios; **Columnas de esta boleta** permite ajustar títulos, orden, posiciones y anchos.

La foto sigue siendo una referencia. La salida utiliza el documento limpio y editable. El OCR y la tipografía pueden necesitar correcciones al comparar con el original.

## Validación

Versión `0.10.0`, código `12`, paquete `com.boleta.editor`, arquitectura `arm64-v8a`. Compilación y firma verificadas; **118 pruebas automatizadas aprobadas**, sin fallos ni errores. Lint sin errores (46 advertencias).

Se comprobaron cálculos, fecha local, conservación de datos, movimientos, altas/bajas de productos, alineación del pie, Deshacer y exportación desde la interfaz Android. El PDF de prueba es válido y la imagen extraída de él coincide **píxel por píxel** con el PNG de la vista previa limpia.

Queda pendiente la prueba en un teléfono físico. La configuración y prueba de la impresora POS-8001DD se posponen por petición del usuario.

Este repositorio contiene instaladores, sus ZIP, sumas SHA-256 y esta guía. No contiene fotos de boletas, claves ni datos del teléfono. Consulta [SHA256SUMS.txt](SHA256SUMS.txt) para verificar los archivos. Se conservan las versiones anteriores como respaldo.
