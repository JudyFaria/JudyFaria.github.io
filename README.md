# Portfólio — Judy Beatriz Faria dos Santos

Site de portfólio pessoal em HTML/CSS/JS puro, sem dependências externas nem
build step.

## Rodar localmente

Basta abrir `index.html` no navegador, ou servir a pasta com um servidor
estático simples:

```bash
python3 -m http.server 8000
```

e acessar `http://localhost:8000`.

## Publicar

Como o site é 100% estático, funciona sem alterações em qualquer uma destas opções:

- **GitHub Pages**: crie um repositório (ex: `JudyFaria.github.io` para domínio
  raiz, ou qualquer nome + habilitar Pages nas configurações do repo apontando
  para a branch `main`, pasta `/`).
- **Netlify**: arraste a pasta `portfolio/` no painel do Netlify, ou conecte o
  repositório Git (sem build command, publish directory = `.`).
- **Vercel**: importe o repositório e defina o "Output Directory" como `.`
  (sem framework/build step).

## Estrutura

```
portfolio/
├── index.html
├── css/style.css
├── js/script.js
└── assets/
    ├── foto-perfil.jpg
    ├── curriculo-judy-faria-santos.pdf
    └── favicon.svg
```
