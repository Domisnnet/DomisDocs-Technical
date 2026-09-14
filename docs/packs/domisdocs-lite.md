---
title: DomisDocs Lite - R$49 - Next.js 15 Starter
description: Boilerplate Next.js 15 + Tailwind v4 + shadcn + Firebase Killer + Fix Angular 17-20. Entrega via repo privado DomisPacks-Technical
next:
  text: "💎 DomisDocs Pro - R$197"
  link: "/packs/domisdocs-pro"
prev:
  text: "Vitrine - Todos os Packs"
  link: "/packs/"
---

::: info 🚀 LITE - R$49 | NEXT.JS 15 STARTER | REPO PRIVADO DomisPacks-Technical
Boilerplate Next.js 15 + Tailwind v4 + shadcn/ui + Firebase Killer. Inclui como bônus o fix definitivo para deploy Angular 17-20 no Firebase Hosting.
:::

# 🚀 DomisDocs Lite - R$49

> Fix em 5 minutos para `Could not find public directory` + 404 SPA + Starter Next.js 15 pronto.

## Repositórios - Referência

**Vitrine Pública:** `DomisDocs-Technical` - Documentação aberta em domisdocs-602fc.web.app
**Entrega Privada:** `DomisPacks-Technical` - Repositório privado após pagamento na Kiwify

## O que esta página documenta

Esta página documenta o Pack Lite disponível em `packs` na plataforma.

### Stack do Lite

- Next.js 15 + App Router + Turbopack
- Tailwind CSS v4 + shadcn/ui
- Firebase Hosting Frameworks + firebase.json killer
- firestore.rules básica
- Bônus: firebase.json corrigido para Angular 17-20

### O que vem no Lite

```
DomisPacks-Technical/templates/domisdocs-lite/
├── firebase.json -> public: dist/browser + rewrites + cache 1 ano
├── .firebaserc
├── firestore.rules -> básica validada
├── next.config.js -> otimizado Firebase
├── tailwind.config.ts -> v4 configurado
└── src/
    └── lib/firebase.ts
```

### firebase.json de referência

```json
{
  "hosting": {
    "public": "dist/domisdocs/browser",
    "ignore": [
      "firebase.json", 
      "**/.*", 
      "**/node_modules/**"
    ],
    "rewrites": [
      { "source": "**", "destination": "/index.html" }
    ],
    "headers": [
      {
        "source": "**/*.@(js|css)",
        "headers": [
          { "key": "Cache-Control", "value": "max-age=31536000" }
        ]
      }
    ]
  }
}
```

Resolve:

- Error: Could not find public directory: dist/seu-app/browser
- Error: 404 on refresh - página não encontrada ao dar F5

## Instalação - Referência Documental

Fluxo Oficial:

1. Paga na Kiwify - Recebe PRO_KEY por e-mail
2. Aceita convite GitHub - Domisnnet invited you to DomisPacks-Technical
3. Instala Via CLI :

```bash
npm create domis@latest
  🔥 DomisPacks Technical v1.0.24
  ? Qual pack você quer acelerar hoje?
  > 🔥 DomisDocs Lite — Next.js 15 + Tailwind v4 + Firebase Killer
  ? Digite sua PRO_KEY: ********************
```

4. Faz o Deploy :

```bash
ng build
firebase deploy --only hosting
```

Ou para Next.Js 15 :

```bash
npm run build
firebase deploy --only hosting
```

## FAQ - Lite

::: details Funciona no Angular 20?
Sim. Validado em Angular 17, 18, 19 e 20 com application builder e browser folder. O firebase.json já aponta para dist/seu-app/browser.
:::

::: details Preciso ter o DomisPacks-Technical antes?
Não. Você paga na Kiwify e recebe convite automático para o repositório privado Domisnnet/DomisPacks-Technical + PRO_KEY.
:::

::: details O que acontece depois que eu pagar?

1. Kiwify envia PRO_KEY na hora
2. GitHub envia convite para repo privado
3. Você clona com GH_TOKEN
:::

::: details Qual a diferença para o Pro?
Lite = Next.js 15 Starter + fix deploy (firebase.json + rewrites). Pro = Lite + firestore.rules + storage.rules + CI/CD + SSR + Stripe + Kiwify Webhook + Dashboard SaaS.
:::

## Comparativo

| Recurso                           | Lite R$49        |
| :-------------------------------- | :--------------- |
| Fix public directory + 404 SPA    | ✅               |
| Cache 1 ano + Compressão          | ✅               |
| Next.js 15 + Tailwind v4 + shadcn | ✅ Starter       |
| firestore.rules seguro            | ❌ básica apenas |
| storage.rules                     | ❌               |
| GitHub Actions                    | ❌               |
| Functions SSR + Stripe            | ❌               |

## 💬 O que quem comprou está dizendo

<div 
  style="margin: 32px 0; 
  padding: 28px; 
  background: rgba(255,255,255,0.03); 
  border-radius: 16px; 
  border: 1px solid rgba(38,255,0,0.15);"
>
  <div style="
    display: flex; 
    gap: 16px; 
    align-items: flex-start;"
  >
    <div style="
      display: flex; 
      align-items: center; 
      justify-content: center;
      width: 48px; 
      height: 48px; 
      border-radius: 50%; 
      background: linear-gradient(135deg, #26FF00, #00D4FF);  
      font-weight: 800; 
      color: #000; 
      flex-shrink: 0;">R</div
    >
    <div style="flex: 1;">
      <div style="
        display: flex; 
        align-items: center; 
        gap: 8px; 
        margin-bottom: 8px; 
        flex-wrap: wrap;"
      >
        <span style="font-weight: 700; font-size: 16px; color: #fff;">Rafael M.</span>
        <span style="font-size: 13px; opacity: 0.6;">· Dev Front-end · São Paulo</span>
        <span style="margin-left: auto; color: #FFD700;">★★★★★</span>
      </div>
      <p style="
        font-size: 15px; 
        line-height: 1.6; 
        margin: 12px 0; 
        font-style: italic; 
        color: #e5e7eb;"
      >
        "Tava há 2 dias travado no erro &nbsp;<code>Could not find public directory</code> nbsp; no Next.Js 15. Tentei de tudo no Stack Overflow. Comprei o Lite por R$49 achandoque era  gambiarra,     mas é o <code>firebase.json</code> certo mesmo. Copiei, deicode>ng build</<code> e   <code>firebase    deploy --only hosting</code> e subiu deprimeira. Valeu cada centavo."
      </p>
      <div style="
        display: flex; 
        gap: 12px; 
        margin-top: 12px; 
        font-size: 12px; 
        opacity: 0.5; 
        flex-wrap: wrap;"
      >
        <span>✅ Compra verificada na Kiwify</span>
        <span>·</span>
        <span>📅 Há 3 dias</span>
        <span>·</span>
        <span style="color: #26FF00;">🚀 DomisPacks-Technical</span>
      </div>
    </div>
  </div>
</div>

## 🛒 Comprar DomisDocs Lite - R$49

<div style="
  margin: 24px 0; 
  padding: 28px; 
  background: linear-gradient(135deg, #0a0a1a, #1a1a0a); 
  border-radius: 20px; 
  border: 2px solid #FFD700; 
  text-align: center; 
  box-shadow: 0 8px 32px rgba(255,215,0,0.3);"
>
  <h3 style="
    color: #ffffff !important; 
    font-size: 24px; 
    font-weight: 900; 
    margin-bottom: 8px;"
  > 🔥 DOMISDOCS LITE - R$49</h3>
  <p style="
    color: #FFD700 !important; 
    font-size: 16px; 
    font-weight: 700; 
    margin: 8px 0;"
  > Fix Next.js 15 + Tailwind v4 + shadcn em 5 minutos</p>
  <p style="
    color: #e5e7eb !important; 
    font-size: 14px; 
    margin: 12px 0;"
  >
    ✅ CLI <code>npm create domis@latest</code> + Repo Privado<br/>
    ✅ 6 meses de updates + Uso VITALÍCIO<br/>
    ✅ Licença Comercial Privada v1.2
  </p>
  <a href="https://pay.kiwify.com.br/heAmetM" target="_blank" style="
    display: inline-block; 
    margin: 16px 0; 
    padding: 16px 32px; 
    background: linear-gradient(90deg, #FFD700, #FFA500); 
    color: #000000 !important; 
    font-weight: 900; 
    font-size: 18px; 
    border-radius: 12px; 
    text-decoration: none; 
    box-shadow: 0 4px 16px rgba(255,215,0,0.4);"
  > 🚀 QUERO MEU ACESSO AGORA - R$49</a>
  <div style="margin-top: 12px;">
    <a href="https://kiwify.app/L2NNYK8" target="_blank" style="
      color: #9ca3af !important; 
      font-size: 13px; 
      text-decoration: underline;"
    > Ver página oficial de vendas</a>
  </div>
  <p style="
    color: #26FF00 !important; 
    font-size: 12px; 
    margin-top: 16px; 
    font-weight: 700;"
  > ⚡️ Entrega automática via PRO_KEY por e-mail após pagamento</p>
</div>
&nbsp;

::: tip Quer produção completa?
Conheça o Pro R$197 com Rules + CI/CD + SSR + Stripe + Dashboard. Veja em [DomisDocs Pro →](/packs/domisdocs-pro)
:::

## 🛡 Garantia

Todos os packs têm **7 dias de garantia incondicional** via Kiwify. Não funcionou? Reembolso total.
