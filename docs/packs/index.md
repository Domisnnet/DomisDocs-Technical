---
title: Packs Premium - Vitrine Oficial
description: Templates prontos para produção - Next.Js 15 + Tailwind v4 + Lite R$49 e Pro R$197
outline: deep
next:
  text: '🚀 DomisDocs Lite - R$49'
  link: '/packs/domisdocs-lite'
prev: false
---

::: info 📦 VITRINE: DOMISDOCS - NEXT.JS 15 + SAAS BOILERPLATE
Loja Oficial de templates de produção. Entrega direta via Firebase Storage com PRO_KEY. Stack: Next.Js 15 + Tailwind v4 + shadcn/ui + Firebase Killer + Functions v2 kiwifyWebhook, verifyProKey, ping.
:::

# 🛒 Packs Premium - Next.Js 15 + SaaS Boilerplate

> **Vitrine Pública:** `DomisDocs-Technical` - Documentação aberta com base Angular 20 + Firebase. Domínio domisdocs-602fc.web.app. Build docs/.vitepress/dist

## O que esta plataforma contém:

### 1. DomisDocs-Technical - Público:

- Documentação Open Source da stack Angular 20 + Firebase Hosting + Functions Node 22. 

> É aqui que está o docs/.vitepress/dist. Deploy &nbsp;`--only hosting.`

### 2. DomisPacks Premium - Entrega Direta via Storage:

Packs disponíveis em `packs` na Plataforma:

- Lite: Next.Js 15 + SaaS Boilerplate - base limpa para começar

- Pro: Tudo do Lite + Stripe Checkout + Firebase Killer 
> Functions: &nbsp;`functions/index.js` , &nbsp;`onRequest` com &nbsp;`secrets["KIWIFY_WEBHOOK_TOKEN"]` , `safeEqual` com &nbsp;`timingSafeEqual` , `generateProKey() : DOMIS-XXXX-XXXX-XXXX` , `pro_keys` com &nbsp;`expires_at +6 meses` , `verifyProKey` com &nbsp;`?key=&pack=lite|pro` retornando `downloadUrl` com &nbsp;`firebaseStorageDownloadTokens` e &nbsp;`ping` + liberação automática via Kiwify.

- Esse repo DomisDocs-Technical faz deploy só de `--only hosting` &nbsp;. As Functions de entrega ficam no deploy `--only functions`

## Packs Disponíveis:

### 🚀 DomisDocs Lite - R$49

**Next.Js 15 Starter - Fix essencial + Starter Next.Js 15 + Tailwind v4**

Resolve:
- Could not find public directory: dist/seu-app/browser
- 404 on refresh nas rotas SPA
- firebase.json corrigido + cache + rewrites
- Next.Js 15 + Tailwind v4 + shadcn/ui + Firebase Hosting Frameworks

Ideal para: Subir projeto hoje em 5 minutos e já começar SaaS em Next.Js 15.

Entrega: &nbsp;`templates/domisdocs-lite.zip` via &nbsp;`verifyProKey` com &nbsp;`downloadUrl` direto do Storage.

[📖 Ver Detalhes e Comprar Lite →](/packs/domisdocs-lite)

---

### 💎 DomisDocs Pro - R$197

**SaaS Completo Next.Js 15 - O que empresas cobram R$2.000**

Tudo do Lite +:
- firestore.rules + storage.rules seguros (produção)
- GitHub Actions - Auto Deploy (git push = deploy)
- Cloud Functions v2 Node 22: 
> `kiwifyWebhook` com &nbsp;`safeEqual` , `verifyProKey` com &nbsp;`expired|inactive|upgrade_required` + &nbsp;`downloadUrl` via Storage Token , `ping`
- Headers de Segurança HSTS, CSP
- SaaS Boilerplate Next.Js 15 + Tailwind v4 + Stripe + PRO_KEY Automática + Dashboard Premium
- Suporte Prioritário + Updates Vitalícios

Ideal para: Projetos de clientes, produção real, SEO, SaaS com pagamento.

> Entrega: &nbsp;`templates/domisdocs-pro.zip` via &nbsp;`verifyProKey?pack=pro` com download direto.

[💎 Ver Detalhes do Pro →](/packs/domisdocs-pro)

## Comparativo - Referência Documental

| Recurso | Lite R$49 | Pro R$197 |
| :--- | :---: | :--- |
| Fix public directory + SPA Rewrite | ✅ | ✅ |
| Cache 1 ano | ✅ | ✅ |
| Next.Js 15 + Tailwind v4 + shadcn | ✅ Starter | ✅ SaaS Completo |
| firestore.rules + storage.rules seguro | ❌ | ✅ |
| GitHub Actions CI/CD | ❌ | ✅ |
| SSR + Functions v2 kiwifyWebhook, verifyProKey, ping + pro_keys | ❌ | ✅ |
| Headers Segurança | ❌ | ✅ |
| Dashboard SaaS Premium | ❌ | ✅ |

## Como funciona a entrega:

```
1. Você paga na Kiwify - PIX ou Cartão
   ↓
2. Recebe por e-mail sua PRO_KEY
   ↓
3. Instala via CLI:
   npm create domis@latest   
```

### Dúvidas Frequentes:

- DomisDocs-Technical: Documentação Pública, Guias gratuitos, Vitrine - este site. Fica em: 
> github.com/Domisnnet/DomisDocs-Technical - Build docs/.vitepress/dist - Deploy --only hosting
- Entrega atual é direta via Firebase Storage: 
> `templates` + Firestore `pro_keys` + Functions `kiwifyWebhook, verifyProKey, ping`

## Mapa de Recursos da Plataforma:

| Módulo | Documenta |
| :--- | :--- |
| Deploy Angular 20 + Firebase | Guia completo do zero ao publicado - build, rotas SPA, rewrites e checklist de produção |
| SaaS Next 15 + Tailwind v4 | Boilerplate com App Router, shadcn/ui, Tailwind v4 e estrutura pronta para SaaS |
| Stripe Checkout Pronto | Integração de pagamento, webhooks e liberação automática de acesso Pro via pro_keys |
| Bônus Firebase Killer | Hosting + Functions v2 + Firestore pro_keys + Storage templates/ com firebaseStorageDownloadTokens |
| Automação Kiwify + CLI | Webhook kiwifyWebhook gera PRO_KEY DOMIS-XXXX-XXXX-XXXX com crypto.randomBytes(6) + expires_at +6 meses e libera download via verifyProKey |
| Troubleshooting e Boas Práticas | Erros reais de deploy (public, functions timeout, Node 22) resolvidos e documentados + verifyProKey com upgrade_required |

## 🛡 Garantia

Todos os packs têm **7 dias de garantia incondicional** via Kiwify.