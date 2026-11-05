# Dead By Dead — gerar o APK

Requisitos: Node 18+, Android Studio (SDK + JDK 17).

1. `npm run setup` — instala o Capacitor, cria a pasta `android/` e aplica horizontal/tela cheia.
2. `npm run apk` — gera `android/app/build/outputs/apk/debug/app-debug.apk` (ou abra a pasta `android/` no Android Studio: Build > Build APK).
3. Para atualizar o jogo: edite `www/index.html` e rode `npm run sync`.

O jogo é um único arquivo HTML sem dependências externas (nenhuma biblioteca, imagem ou fonte remota), então funciona offline no WebView. Toque, joystick e botões já são o controle principal; teclado e mouse são opcionais.
