# TreinoGuiado 40+ Landing Page

Landing page estática para `treinoguiado.com.br`.

## URLs

- Site público: https://treinoguiado.com.br
- Web app: https://app.treinoguiado.com.br
- WhatsApp Codertec: https://wa.me/5541988615268

## Estrutura

```text
public/
  index.html
  css/styles.css
  js/main.js
  img/
wrangler.toml
```

Para visualizar localmente, abra `public/index.html` no navegador.

## Deploy

```bash
npm install
npm run deploy
```

O deploy usa Cloudflare Workers Static Assets via Wrangler, com os assets apontando para `./public`.
