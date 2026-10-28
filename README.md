# SpanishHub AI — proyecto Android inicial

Interfaz Android en español para Samsung. Este paquete crea un APK de demostración mediante GitHub Actions, sin FAL AI ni claves de API.

## Qué incluye
- Aplicación Android sencilla con WebView y una interfaz local en español.
- Secciones para Chat IA, Vídeos, Imágenes, Galería y Ajustes.
- Flujo de compilación automática con GitHub Actions para generar un APK de depuración.

## Importante
Este es un **prototipo de interfaz**, no un generador de vídeos funcional. El archivo `ai_video_generator.py` aportado depende de componentes internos de otro proyecto y de la API de FAL; no se puede integrar directamente en Android ni funcionará sin adaptar el motor. Este paquete no incluye un motor local de generación de vídeo. Para añadirlo habría que elegir e integrar un modelo compatible, y comprobar si puede ejecutarse en el dispositivo. No se garantiza generación explícita, rendimiento ni disponibilidad gratuita.

## Cómo obtener el APK desde Android
1. Crea una cuenta en GitHub si no tienes una.
2. Crea un repositorio nuevo y sube **todos los archivos de esta carpeta**.
3. Abre la pestaña **Actions** del repositorio.
4. Selecciona el flujo **Build SpanishHub AI APK** y pulsa **Run workflow** si no empieza automáticamente.
5. Cuando termine, abre la ejecución y descarga el artefacto `SpanishHubAI-debug-apk`.
6. Descomprime el artefacto y abre el APK en tu Samsung. Android puede pedir permiso para instalar aplicaciones desde esa fuente.

El APK de depuración no está firmado para publicación en Play Store.
