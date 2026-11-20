# Gorros de Egresados – proyecto Android (APK)

App nativa mínima (WebView) que contiene la webapp de control de gorros. Funciona sin internet y guarda los datos en el teléfono.

## Opción A: APK desde GitHub (sin instalar nada)
1. Creá un repositorio en GitHub y subí TODO el contenido de esta carpeta (incluida `.github`).
2. Entrá a la pestaña **Actions** → "Compilar APK" (corre solo al subir; o "Run workflow").
3. Cuando termine (3-5 min), abrí la ejecución y bajá **gorros-egresados-apk** (zip con `app-debug.apk`).
4. Pasalo al celular, abrilo y permití "instalar apps de origen desconocido".

## Opción B: Android Studio
1. File → Open → elegí esta carpeta y esperá el Gradle Sync (si pide Gradle, aceptá 8.7 / JDK 17).
2. Build → Build APK(s). Queda en `app/build/outputs/apk/debug/app-debug.apk`.

## Datos
Se guardan en el almacenamiento interno de la app. Si la desinstalás se borran.
