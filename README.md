# Boleta Studio 0.9

**[Descargar actualización 0.9 para Android](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.9.apk)**

[Descargar el mismo APK en ZIP](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.9.zip)

Conserva el editor limpio y editable de 0.8. La importación completa utiliza la posición de las palabras para reconocer las columnas y filas de cada foto: títulos, orden, ancho y alineación. Si la foto tiene **CODIGO / DESCRIPCION / CANT / IMPORTE FINAL**, la plantilla utiliza esas columnas sin añadir U.M., precio unitario ni descuento. También reconoce formatos con cantidad al principio o descripción encima de los valores.

## Instalar como actualización

1. Abre el enlace del APK en Chrome desde tu celular y acepta la descarga.
2. En Chrome, abre **⋮ → Descargas** y toca `Boleta-Studio-0.9.apk`.
3. Si Android solicita permiso para instalar desde Chrome, concédelo y regresa al instalador.
4. Pulsa **Actualizar**, conservando instalada la aplicación anterior y sus datos.

Android ARM64, Android 6 o posterior, mismo paquete y firma que las versiones anteriores. El ZIP contiene el mismo APK y debe extraerse primero. Los avisos automáticos dentro de la app siguen pendientes.

## Ajustar la boleta que ya tienes

1. Abre tu boleta y pulsa **Plantillas → Ajustar distribución a la foto → Ajustar**.
2. La app usa su foto de referencia guardada y ajusta la tabla, las filas de fecha/boleta, caja/cajero y los totales que pueda reconocer. Conserva los nombres y precios actuales; reemplaza esos ajustes de distribución.
3. Revisa **2. Vista previa**. Toca los textos para corregirlos; usa **Mover** para colocar textos o líneas y el punto azul para ajustar el ancho.
4. En **Plantillas → Columnas de esta boleta** puedes corregir títulos, orden, alineación, posición, ancho o visibilidad y añadir o quitar columnas.
5. Pulsa **Guardar** para actualizar tu plantilla, o guarda una copia con otro nombre.

Instalar la actualización no cambia por sí solo tus plantillas. El ajuste a la foto se aplica cuando lo eliges. Si no se reconocen las columnas, el ajuste conserva el diseño anterior y permite revisarlas manualmente.

## Otras fotos y productos

- Al importar una foto como **Crear plantilla completa nueva**, se analiza su propia estructura.
- Importar solo productos conserva la distribución de la plantilla actual.
- Los productos añadidos se colocan en las columnas guardadas. El código tiene un campo independiente si está separado en la foto.
- Fecha y número pueden compartir una fila, caja/cajero otra y descuento/vuelto/importe otra, según lo reconocido. No se duplican títulos o números centrados ausentes en el original.
- Los separadores reconocidos de la tabla se convierten en líneas editables entre renglones y acompañan a los productos al añadirlos.
- Los títulos adicionales, como LOTE, se conservan como columnas de texto editable. No se infieren fórmulas de cálculo para esos datos.

Se mantienen **Solo precios**, las plantillas guardadas, el logo/QR, el ajuste de letras al ancho, deshacer, PDF e impresión por Wi-Fi o USB. La foto se usa de referencia; la salida sigue siendo limpia, sin el papel fotografiado como fondo. El QR conserva su contenido al editar los importes.

La detección depende del OCR y de la claridad y el recorte de la foto. Revisa valores y posiciones, sobre todo con formatos nuevos. La fuente exacta y la coincidencia física de la impresión requieren ajuste; no se garantiza una copia idéntica de cualquier boleta.

## Validación

Versión `0.9.0`, código `11`, paquete `com.boleta.editor`, arquitectura `arm64-v8a`. Compilación y firma verificadas; **98 pruebas automatizadas aprobadas**, sin fallos ni errores. Lint sin errores (39 advertencias).

Incluye casos de distintas distribuciones, columnas adicionales, filas de datos e importes, conservación de precios, edición del código por separado, guardado/lectura y posición de separadores al añadir productos. Las pruebas de reconocimiento utilizan posiciones de palabras sintéticas. Falta verificar OCR real, teclado/gestos e impresión en el teléfono y la POS-8001DD físicos.

Este repositorio contiene únicamente instaladores, sus ZIP, sumas SHA-256 y esta guía; no contiene fotos de boletas, sesiones, claves ni datos del teléfono. Consulta [SHA256SUMS.txt](SHA256SUMS.txt) para verificar los archivos. Las versiones anteriores se conservan como respaldo.
