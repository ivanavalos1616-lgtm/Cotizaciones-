MiCotizador - proyecto Android

IMPORTANTE:
Este archivo es el PROYECTO FUENTE, no un APK ya compilado.
Incluye una aplicación web local dentro de un contenedor Android (WebView) y un flujo de GitHub Actions para compilar un APK debug.

Compilar desde el celular:
1. Descomprime el ZIP.
2. Sube todos los archivos a un repositorio nuevo de GitHub (puedes hacerlo desde Chrome con la opción Sitio para computadoras).
3. En GitHub abre la pestaña Actions y habilita los workflows si te lo pide.
4. Ejecuta el workflow "Construir APK".
5. Cuando termine correctamente, abre la ejecución y descarga el artefacto "MiCotizador-debug-apk".
6. Descomprime el artefacto y toca el APK para instalarlo. Android puede pedir autorización para instalar apps de esa fuente.

La compilación requiere una cuenta de GitHub y conexión a internet. No compartas contraseñas ni tokens con nadie.

Funciones incluidas en esta primera versión:
- Nombre del negocio editable.
- Teléfono y dirección editables.
- Catálogo de materiales con unidad, precio y cantidad.
- Cálculo de subtotal, descuento e IVA.
- Guardado local en el teléfono mediante almacenamiento del navegador WebView.
- Vista imprimible/guardar como PDF desde la función de impresión del Android si está disponible.

Limitaciones de esta versión:
- No incluye selección de logotipo ni un botón nativo dedicado para generar/compartir PDF.
- No se ha probado en tu dispositivo.
