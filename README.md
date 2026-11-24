# Pixel Runner (HTML5) — projeto Android

Casca Android (WebView) em volta do port HTML5 do Pixel Runner. O jogo fica em `app/src/main/assets`.

## Gerar o APK — opção A: Android Studio
1. Instale o Android Studio e abra esta pasta (File > Open).
2. Espere o Gradle sincronizar.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. O arquivo sai em `app/build/outputs/apk/debug/app-debug.apk`.

## Opção B: GitHub Actions (sem instalar nada)
1. Crie um repositório no GitHub e envie o conteúdo desta pasta.
2. Aba Actions > "Build APK" > Run workflow.
3. Baixe o artefato `PixelRunner-debug-apk`.

## Instalar no celular
Copie o `app-debug.apk` para o aparelho, abra e permita "instalar apps desconhecidos".
Android 14 do Galaxy A55 aceita (targetSdk 34, minSdk 24).

Créditos do jogo original: Karl Woditsch (código) e Florent Lacroix (arte), licença Apache 2.0.
