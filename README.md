# Boleta Studio para Android

## Descargar actualización 0.11.0

[Descargar APK para Android — aproximadamente 24 MB](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.11.apk)

[Descargar el mismo APK comprimido en ZIP](https://github.com/patricksotomayor0111-star/boleta-studio-descargas/raw/refs/heads/main/Boleta-Studio-0.11.zip)

1. Abre el enlace del APK en Chrome desde tu celular y acepta la descarga.
2. En Chrome, abre **⋮ → Descargas** y toca `Boleta-Studio-0.11.apk`.
3. Si Android pide permiso para instalar desde Chrome, concédelo y vuelve al instalador.
4. Pulsa **Actualizar**. Conserva instalada la aplicación anterior para mantener tus datos y plantillas.

Android ARM64, Android 6 o posterior. Mismo paquete y firma que las versiones anteriores. El ZIP contiene el mismo APK y debe extraerse primero. Los avisos automáticos dentro de la app siguen pendientes.

## Varios códigos de barras y QR

Abre **Plantillas → Códigos de barras y QR**. Puedes añadir un código escribiendo su contenido, leer una imagen o recortar uno de la foto original. También está **Vista previa → + Añadir → Código de barras o QR**.

Cada código guarda por separado su tipo, número completo, ceros iniciales, posición, ancho, alto y textos encima/debajo. Los códigos que se pueden leer se reconstruyen con barras nítidas y margen blanco. EAN y UPC requieren el número completo con su dígito de control. En la vista previa puedes moverlos, ensancharlos, llevarlos a la papelera y recuperarlos con **Deshacer**.

Una importación completa de foto intenta leer sus códigos automáticamente. Si un recorte no se puede leer, se conserva como imagen para revisarlo; puedes escribir el contenido completo y elegir el tipo para reconstruirlo. Las opciones para actualizar MONTO o la fecha cambian esos rótulos impresos y conservan el contenido original del código.

## Reverso dentro de la misma plantilla

1. Pulsa **Reverso** en la pantalla principal.
2. Usa **Importar reverso**, ajusta las cuatro esquinas y revisa los textos reconocidos.
3. En **Editar datos**, corrige el texto superior, condiciones y mensaje final. En **Logo**, importa o recorta el logo por separado.
4. **Mover diseño** permite mover y editar textos, cambiar su alineación y añadir/quitar líneas. **Orden y tamaños** reorganiza los bloques.
5. **Vista completa** muestra el reverso con el mismo ancho y largo del frente. Activa **Repetir diseño** si quieres repetir el módulo a lo largo del papel.
6. Pulsa **Guardar**, vuelve al frente y usa **Guardar** en la vista previa para guardar o actualizar la plantilla con nombre.

Frente, reverso y códigos se guardan juntos. Si el rollo ya trae publicidad al reverso, puedes guardar e imprimir solo el frente.

## PDF de una o dos caras

Con el reverso activado, **Guardar PDF** ofrece **Solo frente**, **Solo reverso** o **Ambas caras**. Ambas genera dos páginas del mismo tamaño, una por cara. El PDF conserva las imágenes limpias de las vistas previas sin los controles del editor y sin sustituir sus letras.

La fecha y hora actuales se toman al guardar el PDF si esa opción está activada. El archivo guardado conserva ese instante. La preparación y prueba de la impresora física se revisarán después, según lo acordado.

## Productos, IGV, pago y vuelto

Cada producto permite seleccionar **Gravado**, **Exonerado** o **Inafecto**, y un porcentaje de IGV propio opcional. En **Importes**, el cálculo automático actualiza los importes, las tres bases, el IGV, el total, el total en letras y las unidades. El descuento general se reparte proporcionalmente antes de calcular el impuesto.

**Los precios incluyen IGV** obtiene la base y el impuesto desde el total. Desactívalo si corresponde añadir el IGV. En **Pago y vuelto**, escribe **Pagó con** y la forma de pago; se calcula el vuelto y, si falta dinero, se muestra el saldo pendiente. Un pago vacío conserva el vuelto importado.

Se reconocen también recibos como el ejemplo Makro: código y descripción seguidos de cantidad/precio/importe sin un encabezado de columnas. Se conservan los rótulos de sus operaciones, total en letras, unidades y forma de pago. El texto y la distribución reconocidos pueden necesitar correcciones al compararlos con la foto.

## Mejoras anteriores conservadas

Los productos nuevos se colocan antes de la línea de cierre; los totales acompañan la tabla. Los textos, precios y líneas son movibles y editables en la vista previa, con papelera y Deshacer. **Diseño → Letra de todos los productos** fija un tamaño común. El resumen admite alineación izquierda, centro, derecha y justificada.

Las plantillas anteriores siguen disponibles. Se mantienen los ajustes de ancho y columnas según la foto y la corrección del hueco antes de la fecha. **Plantillas → Quitar espacio antes de la fecha** permite aplicarla manualmente, con Deshacer.

## Validación

Versión `0.11.0`, código `15`, paquete `com.boleta.editor`, arquitectura `arm64-v8a`. Compilación y firma comprobadas. **162 pruebas automatizadas aprobadas**, sin fallos, errores ni omitidas. Lint: 0 errores y 69 advertencias.

Se comprobaron códigos, ceros iniciales, dígitos de control, movimientos, persistencia de ambas caras, plantillas antiguas, interfaz de edición, cálculos mixtos y elección de páginas del PDF. Los PDF se validaron con un lector estricto: una imagen por página, dimensiones iguales entre caras e imágenes extraídas idénticas píxel por píxel a sus respectivas vistas previas.

Quedan pendientes las pruebas en el teléfono físico, incluido el reconocimiento ML Kit desde cámara. Las pruebas automáticas de lectura de códigos usan ZXing. La impresora física sigue pendiente por petición del usuario.

Este repositorio contiene instaladores, sus ZIP, sumas SHA-256 y esta guía. No contiene fotos de boletas, claves ni datos del teléfono. Consulta [SHA256SUMS.txt](SHA256SUMS.txt) para verificar los archivos. Se conservan los instaladores anteriores como respaldo.
