# Boleta Studio 0.7.1

**[Descargar actualización 0.7.1 para Android](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.7.1.apk)**

[Descargar el mismo APK en ZIP](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.7.1.zip)

Esta corrección devuelve la plantilla limpia: **fondo blanco y todos los datos como textos editables**, conservando las posiciones de la foto. Solo el logo y el QR se dibujan como imágenes separadas.

## Instalar como actualización

1. Abre el enlace del APK en Chrome desde tu celular y acepta la descarga.
2. En Chrome, abre **⋮ → Descargas** y toca `Boleta-Studio-0.7.1.apk`.
3. Si Android solicita permiso para instalar desde Chrome, concédelo y regresa al instalador.
4. Pulsa **Actualizar**, conservando instalada la aplicación anterior y sus plantillas.

Es un instalador de prueba para Android ARM64, Android 6 o posterior, con el mismo paquete y firma que las versiones anteriores. El ZIP contiene el mismo APK y debe extraerse primero. Los avisos automáticos dentro de la aplicación siguen pendientes.

## Tu boleta actual

Al abrir Boleta Studio, espera a que termine **Preparando plantilla limpia…** y entra en **2. Vista previa**. Las plantillas de 0.7 se convierten automáticamente conservando sus datos corregidos y posiciones; la foto del papel deja de imprimirse como fondo.

- En **1. Editar datos** puedes corregir los textos reconocidos, productos e importes.
- En **2. Vista previa** toca un texto para editarlo. Las letras se ajustan al espacio y se conservan las filas.
- **Mover**, el punto azul, la papelera y **Deshacer** permiten ajustar los elementos.
- **Solo precios** actualiza los importes vinculados. Para un vínculo que falte, toca el valor y elige **Vincular dato**.
- Si falta el logo o QR, utiliza **Añadir/Cambiar logo o QR → Recortar de la foto original**. Toca la imagen en la vista previa para ajustar posición y tamaño.
- **Guardar** conserva la plantilla para reutilizarla.

Para otra boleta, en **Importar foto** o **Tomar foto** elige **Crear plantilla nueva respetando la foto** y marca las cuatro esquinas del papel. La foto sirve para obtener las posiciones; el documento final se reconstruye sobre blanco.

En **Diseño** elige el ancho real del papel. Cambiarlo escala la distribución completa; los milímetros no se deducen solo de una foto. Selecciona el ancho de puntos correspondiente en la impresión térmica.

Revisa el texto e importes del OCR: puede equivocarse u omitir datos. Puedes añadir lo que falte con **+ Añadir → Texto editable**. Con cálculo automático desactivado revisa los totales manualmente. El QR conserva su contenido original. La fuente limpia puede diferir de la original.

## Validación

Versión `0.7.1`, código `9`, paquete `com.boleta.editor`, arquitectura `arm64-v8a`. Compilación y firma verificadas; 99 pruebas automatizadas aprobadas y lint sin errores. Se comprobó la conversión de una plantilla 0.7 sin perder textos corregidos y que las manchas de una foto no aparecen en la salida. Los casos espaciales y de extracción de imágenes usan datos sintéticos.

Falta validar OCR real, teclado/gestos e impresión en el teléfono y la POS-8001DD físicos. Haz una primera impresión de prueba. Es una versión de prueba distribuida fuera de Google Play.

Este repositorio contiene únicamente instaladores, sus ZIP, sumas SHA-256 y esta guía; no contiene fotos de boletas, sesiones, claves ni datos del teléfono. Consulta [SHA256SUMS.txt](SHA256SUMS.txt) para verificar los archivos. Se conservan las versiones anteriores como respaldo.
