# Boleta Studio 0.8

**[Descargar actualización 0.8 para Android](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.8.apk)**

[Descargar el mismo APK en ZIP](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.8.zip)

Esta versión vuelve al editor estructurado de la captura elegida por el usuario y corrige el **ancho**. Conserva los campos habituales, la presentación limpia, los productos y los controles de edición, movimiento y eliminación.

## Instalar como actualización

1. Abre el enlace del APK en Chrome desde tu celular y acepta la descarga.
2. En Chrome, abre **⋮ → Descargas** y toca `Boleta-Studio-0.8.apk`.
3. Si Android solicita permiso para instalar desde Chrome, concédelo y regresa al instalador.
4. Pulsa **Actualizar**, conservando instalada la aplicación anterior y sus datos.

Es un instalador de prueba para Android ARM64, Android 6 o posterior, con el mismo paquete y firma que las versiones anteriores. El ZIP contiene el mismo APK y debe extraerse primero. Los avisos automáticos dentro de la app siguen pendientes.

## Ajustar el ancho

1. Abre **2. Vista previa** y toca el texto que quieras ampliar.
2. En la ventana de edición, utiliza **Ancho del cuadro** o **Usar todo el ancho**.
3. Activa **Ajustar letras al ancho del cuadro** y pulsa **Aplicar**.
4. Para la fecha y el número está **Fecha y boleta en la misma fila**: ajusta las letras para que quepan al costado y conserva Caja/turno en su renglón.
5. Pulsa **Guardar** para conservar la plantilla.

El punto azul derecho también modifica el ancho y activa el ajuste de letras. El área está limitada por el papel de impresión. Los demás campos y precios conservan sus datos.

Se mantienen **1. Editar datos**, **Solo precios**, los productos, logo/QR, plantillas guardadas, PDF e impresión por Wi-Fi o USB. La importación vuelve a crear el documento estructurado del editor de la captura.

Si venías de 0.7/0.7.1, se recupera la presentación estructurada. Las correcciones que se puedan ubicar de forma única se incorporan al dato correspondiente; las restantes están conservadas en **Texto OCR completo** para revisar. Se guarda un respaldo interno completo del documento anterior.

## Validación

Versión `0.8.0`, código `10`, paquete `com.boleta.editor`, arquitectura `arm64-v8a`. Compilación y firma verificadas; 79 pruebas automatizadas aprobadas y lint sin errores. Incluye las pruebas de la base 0.6 y casos nuevos de ancho, conservación del diseño/datos, filas de fecha/número, guardado y recuperación de versiones posteriores.

Falta verificar teclado/gestos, OCR real e impresión en el teléfono y la POS-8001DD físicos. Revisa la primera impresión. Es una versión de prueba distribuida fuera de Google Play.

Este repositorio contiene únicamente instaladores, sus ZIP, sumas SHA-256 y esta guía; no contiene fotos de boletas, sesiones, claves ni datos del teléfono. Consulta [SHA256SUMS.txt](SHA256SUMS.txt) para verificar los archivos. Las versiones anteriores se conservan como respaldo.
