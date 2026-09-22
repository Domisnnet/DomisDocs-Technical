---
title: DomisDocs Lite - Next.Js 15 Starter
description: Boilerplate Next.Js 15 + SaaS Boilerplate
next:
  text: "💎 DomisDocs Pro - &nbsp;R$197"
  link: "/packs/domisdocs-pro"
prev:
  text: "Vitrine - &nbsp;Todos os Packs"
  link: "/packs/"
---

::: info 🚀 LITE: NEXT.JS 15 STARTER → &nbsp;ENTREGA DIRETA VIA PRO_KEY
> Boilerplate Next.Js 15 + Tailwind v4 + shadcn/ui + Firebase Hosting Frameworks. 
>
> Deploy otimizado em 5 minutos.
:::
&nbsp;

# 🚀 DomisDocs Lite - R$49

- Fix em 5 minutos para `Could not find public directory` + 404 SPA + Starter Next.Js 15 pronto.

## Referências:

> **Vitrine Pública:** &nbsp;`DomisDocs-Technical` - Documentação Open Source.
>
> **Entrega:** Direta via PRO_KEY + &nbsp;`npm create domis@latest` após pagamento na Kiwify.

## O que esta página documenta?

- Esta página documenta o Pack Lite disponível em `packs` na Plataforma:

### Stack do Lite:

- Next.Js 15 + App Router + Turbopack
- Tailwind CSS v4 + shadcn/ui
- Firebase Hosting Frameworks + firebase.json otimizado
- rewrites SPA + headers otimizados

### O que vem no Lite:

```
templates/domisdocs-lite/
├── firebase.json  → public: dist/browser + rewrites + headers
├── .firebaserc  → básica validada
├── firestore.rules  → básica validada
├── next.config.Js  → otimizado Firebase
├── postcss.config.mjs  → v4 configurado
└── lib/utils.ts
```

### firebase.json de referência

```json
{
  "hosting": {
    "source": ".",
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

- Error: Could not find public directory
- Error: 404 on refresh - página não encontrada ao dar F5

## Instalação - Referência Documental

Fluxo Oficial:

1. Paga na Kiwify - Recebe PRO_KEY por e-mail
2. Instala Via CLI :

```bash
npm create domis@latest
  🔥 DomisDocs CLI v1.0.37
  ? Qual pack você quer acelerar hoje?
  > 🔥 DomisDocs Lite — Next.Js 15 + Tailwind v4 + Firebase
  ? Digite sua PRO_KEY: ********************
```

3. Faz o Deploy :

```bash
npm run build
firebase deploy --only hosting
```

## FAQ - Lite

::: details Funciona no Next.Js 15 com App Router?
Sim. Validado no Next.Js 15 com App Router + Turbopack. O firebase.json já vem otimizado para Firebase Hosting Frameworks.
:::

::: details Como recebo o acesso?
Você paga na Kiwify e recebe sua PRO_KEY por e-mail na hora. Depois é só rodar `npm create domis@latest` e digitar a key.
:::

::: details O que acontece depois que eu pagar?
1. Kiwify envia PRO_KEY na hora
2. Você roda `npm create domis@latest`
3. Digita a PRO_KEY e o template é baixado
:::

::: details Qual a diferença para o Pro?
Lite = Next.Js 15 Starter + deploy otimizado (firebase.json + rewrites). Pro = Lite + firestore.rules + storage.rules + CI/CD + Stripe + Kiwify Webhook + Dashboard SaaS.
:::

## Comparativo

| Recurso                               | Lite R$49         |
| :------------------------------------ | :---------------- |
| Fix public directory + 404 SPA        | ✅               |
| Next.Js 15 + Tailwind v4 + shadcn/ui  | ✅ Starter       |
| firestore.rules seguro                | ❌               |
| storage.rules                         | ❌               |
| GitHub Actions                        | ❌               |
| Functions + Stripe                    | ❌               |

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
        "Tava há 2 dias travado no erro <code>Could not find public directory</code> no Next.Js 15. Tentei de tudo no Stack Overflow. Comprei o Lite por R$49 achando que era gambiarra, mas é o <code>firebase.json</code> certo mesmo. Copiei, dei <code>npm run build</code> e <code>firebase deploy --only hosting</code> e subiu de primeira. Valeu cada centavo."
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
  > Fix Next.Js 15 + Tailwind v4 + shadcn em 5 minutos</p>
  <p style="
    color: #e5e7eb !important; 
    font-size: 14px; 
    margin: 12px 0;"
  >
    ✅ CLI <code>npm create domis@latest</code> + PRO_KEY<br/>
    ✅ 6 meses de updates<br/>
    ✅ Licença Comercial Privada v1.03
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
  <p style="
    color: #26FF00 !important; 
    font-size: 12px; 
    margin-top: 16px; 
    font-weight: 700;"
  > ⚡ Entrega automática via PRO_KEY por e-mail após pagamento</p>
</div>
&nbsp;

::: tip Quer produção completa?
Conheça o Pro R$197 com Rules + CI/CD + Stripe + Dashboard. 
> Veja em [DomisDocs Pro →](/packs/domisdocs-pro)
:::

## 🛡 Garantia

> Todos os packs têm **7 dias de garantia incondicional** via Kiwify.
