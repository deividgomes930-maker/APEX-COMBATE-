# APEX COMBATE — projeto Android

Este projeto empacota o jogo HTML enviado em um aplicativo Android (WebView), em modo paisagem.

## Gerar o APK pelo GitHub usando o celular
1. Extraia este ZIP.
2. Crie um repositório no GitHub e envie todos os arquivos e pastas deste projeto.
3. Abra a aba **Actions** do repositório.
4. Escolha **Build APK** e toque em **Run workflow** (ou aguarde o build automático após enviar para `main`).
5. Quando terminar, abra a execução e baixe o artefato **apex-combate-apk**.
6. Dentro do ZIP baixado estará `app-debug.apk`.

## Observações
- O APK carrega `index.html` localmente.
- O jogo ainda usa Three.js e fontes por CDN; portanto, a primeira carga desses recursos precisa de internet.
- Este projeto é uma base de compilação. O APK ainda precisa ser compilado pelo GitHub Actions ou Android Studio.
