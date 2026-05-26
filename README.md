# NT Modas — Catálogo Online

Site catálogo de moda feminina com painel administrativo completo.

## ✨ Funcionalidades

- **Catálogo** com filtro por categoria
- **Modal** de produto com botão de compra direto no WhatsApp
- **Slider de banners** hero com autoplay e swipe mobile
- **Barrinha rotativa** de avisos no topo
- **Painel Admin** protegido por senha com:
  - Gerenciar produtos (adicionar, editar, excluir)
  - **Upload de imagens** via Supabase Storage
  - Gerenciar banners do hero
  - Gerenciar avisos do topo
  - Gerenciar categorias
  - Configurações de WhatsApp e endereço

## 🛠 Tecnologia

- HTML + CSS + JavaScript puro (sem framework)
- [Supabase](https://supabase.com) para storage de imagens
- Dados salvos em `localStorage`

## 🚀 Como usar

1. Abra o `index.html` no navegador **ou** hospede em qualquer servidor estático (GitHub Pages, Vercel, Netlify)
2. Acesse o painel admin clicando no ícone ⊞ no header
3. Senha padrão: `ntmodas2024` (altere em Configurações > Segurança)

## 📦 Hospedagem rápida — GitHub Pages

1. Suba este repositório no GitHub
2. Vá em **Settings → Pages**
3. Source: `Deploy from branch` → `main` → `/ (root)`
4. Aguarde ~1 min e o site estará em `https://seu-usuario.github.io/nt-modas`

## 🔑 Supabase

- Projeto: `Nt Modas` — região São Paulo
- Bucket: `nt-modas-imagens` (público, máx 5MB por imagem)
- Aceita: JPG, PNG, WEBP, GIF
