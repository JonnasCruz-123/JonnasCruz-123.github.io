# Caçada: Heitor, o Bom de Bola 🎮

Jogo de tiro em **pixel art** (HTML5 Canvas, um único `index.html`). Abata inimigos,
junte almas (💀), compre poderes na loja e enfrente 3 chefões em 3 fases:
**Heitor** (campo), **Henrique** (caverna) e a **Tropeira** (inferno).

## Jogar
- Online: https://jonnascruz-123.github.io
- Controles (PC): mover `A/D` ou `←/→` · pular `W`/`↑` · atirar clique · trocar Doze/Laser `Q` · item (Nuke) `Espaço` · foguete botão direito + clique.
- Mobile: joystick, botões de pular / arma / nuke na tela, 2 dedos = foguete.

## Instalar como app (PWA) — jeito mais fácil 📲
O jogo é um **PWA instalável**:
1. Abra https://jonnascruz-123.github.io no navegador do celular (Chrome/Edge).
2. Menu do navegador → **"Instalar app"** / **"Adicionar à tela inicial"**.
3. Abre em tela cheia, paisagem, funciona offline — igual a um app.

## Gerar o APK (arquivo .apk) 🤖
Há um workflow que compila um APK Android automaticamente (Apache Cordova):
1. Aba **Actions** → **Build Android APK** → **Run workflow** (ou ele roda ao mudar o `index.html`).
2. Ao terminar, baixe o APK em **Artifacts → cacada-debug-apk**, ou na **Release `apk-latest`**.
3. No Android, permita "instalar de fontes desconhecidas" e instale o `.apk`.

> É um APK de *debug* (não assinado para a Play Store), mas instala normalmente para uso pessoal/teste.
