# Boleta Studio 0.7

Instalador de prueba para Android ARM64 (Android 6 o posterior).

**[Descargar Boleta Studio 0.7 para Android](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.7.apk)**

[Descargar el mismo instalador en ZIP](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.7.zip)

## Instalar o actualizar

1. Abre el enlace del APK en Chrome desde el celular y acepta la descarga.
2. En Chrome, abre **⋮ → Descargas** y toca `Boleta-Studio-0.7.apk`.
3. Si Android solicita permiso para instalar desde Chrome, concédelo y regresa al instalador.
4. Pulsa **Actualizar**, conservando instalada la aplicación anterior y sus plantillas. Si aún no estaba instalada, pulsa **Instalar**.

Este APK conserva el identificador y la firma de las versiones anteriores. El ZIP contiene el mismo APK y debe extraerse primero. Los avisos automáticos dentro de la aplicación siguen pendientes.

## Adaptar la boleta a su foto

Para tu borrador actual, entra en **Plantillas → Adaptar a la foto → Adaptar**. Utiliza la foto guardada y sustituye las posiciones del borrador; puedes guardar una copia antes si quieres conservar el diseño anterior.

Para otra boleta, en **Importar foto** o **Tomar foto** elige **Crear plantilla nueva respetando la foto**. Marca las cuatro esquinas del papel y pulsa **Enderezar y escanear**.

- La foto recortada determina las posiciones y proporciones de cada boleta.
- Los textos, logo y QR sin editar conservan la tinta de la imagen limpia.
- Toca un texto para editarlo. Las letras se ajustan a su cuadro sin pasar otros datos a otra fila.
- **Mover**, el punto azul, la papelera y **Deshacer** permiten ajustar los elementos detectados.
- **Solo precios** actualiza los importes vinculados. Si falta un vínculo, toca el valor y usa **Vincular dato**.
- Las filas nuevas mantienen las columnas; el pie y el QR se desplazan juntos cuando hace falta ampliar el papel.
- **Guardar** conserva la plantilla para reutilizarla.

En **Diseño** elige el ancho real del papel: 58, 80, 112 mm u otro valor entre 25 y 210 mm. Cambiar el ancho escala la distribución completa. Los milímetros no se pueden deducir solo de una foto. Para impresión térmica, selecciona además el ancho de puntos correspondiente al rollo en **Imprimir**.

El OCR y los importes deben revisarse. Los textos no detectados siguen como imagen; pueden cubrirse y añadirse textos editables. Con cálculo automático desactivado, revisa los totales manualmente. El QR conserva su contenido original. Las arrugas y el desenfoque dependen de la foto; la fuente de un texto editado puede diferir de la original.

## Validación

Versión `0.7.0`, código `8`, paquete `com.boleta.editor`, arquitectura `arm64-v8a`. Compilación y firma verificadas; 93 pruebas automatizadas aprobadas y lint sin errores. Las pruebas espaciales utilizan imágenes y coordenadas sintéticas. Falta validar OCR real, teclado/gestos e impresión en el teléfono y la POS-8001DD físicos. Es una versión de prueba distribuida fuera de Google Play.

Este repositorio contiene únicamente instaladores, sus ZIP y sumas SHA-256 y esta guía; no contiene fotos de boletas, sesiones, claves ni datos del teléfono. Consulta [SHA256SUMS.txt](SHA256SUMS.txt) para verificar los archivos. Se conserva también el instalador anterior 0.6.
