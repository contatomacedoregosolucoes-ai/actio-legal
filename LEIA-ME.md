# Site legal do Actio (Termos + Privacidade) — passo a passo

Estas 3 páginas (início, privacidade e termos) ficam hospedadas **de graça**
no GitHub Pages. A Apple exige esses links funcionando para aprovar o app.

Este repositório pode (e deve) ser **público** — não há nada sensível aqui.

## Passo a passo (~5 minutos)

1. No GitHub, clique no **+** → **New repository**.
   - Nome: `actio-site` → deixe **Public** ✅ → **Create repository**.
2. Clique em **uploading an existing file** e arraste os 3 arquivos desta
   pasta: `index.html`, `privacidade.html`, `termos.html` → **Commit changes**.
3. No repositório: **Settings → Pages** (menu lateral).
   - Em "Build and deployment" → Source: **Deploy from a branch**.
   - Branch: **main** / pasta **/(root)** → **Save**.
4. Aguarde ~1 minuto e recarregue a página. Vai aparecer:
   **"Your site is live at https://SEU-USUARIO.github.io/actio-site/"**

## Seus links finais (para o app e a App Store)

- Política de Privacidade: `https://SEU-USUARIO.github.io/actio-site/privacidade.html`
- Termos de Uso: `https://SEU-USUARIO.github.io/actio-site/termos.html`

⚠️ Depois de publicar, configure a origem HTTPS desses links em
`LEGAL_BASE_URL` na configuração Release do Xcode.
