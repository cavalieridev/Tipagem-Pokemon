# Tipagem Pokémon

Consulta rápida de tipagem Pokémon (18 tipos): defesa, ataque e tabela completa.
PWA instalável — funciona offline depois do primeiro acesso.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `tipagem-pokemon`).
2. Envie estes arquivos:
   ```bash
   git remote add origin https://github.com/SEU-USUARIO/tipagem-pokemon.git
   git push -u origin main
   ```
3. No repositório: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. Acesse `https://SEU-USUARIO.github.io/tipagem-pokemon/` e, no celular,
   toque em **Adicionar à tela inicial** para instalar como app.

## Arquivos

- `index.html` — o aplicativo completo (HTML + CSS + JS em um arquivo)
- `manifest.webmanifest` — manifesto PWA (nome, ícones, modo standalone)
- `sw.js` — service worker (cache offline)
- `icons/` — ícones 192/512 (any + maskable), apple-touch-icon e favicon
