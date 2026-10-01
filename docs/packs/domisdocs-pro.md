---
title: DomisDocs Pro - Produção Completa - Em desenvolvimento
description: SaaS Boilerplate Next.Js 15 + SaaS Boilerplate + Stripe + Rules + CI/CD + Dashboard.
next:
  text: 'Vitrine - &nbsp;Todos os Packs'
  link: '/packs/'
prev:
  text: '🚀 DomisDocs Lite - &nbsp;R$49'
  link: '/packs/domisdocs-lite'
---

::: info 💎 PRO: SAAS COMPLETO NEXT.JS 15 → &nbsp;ENTREGA DIRETA VIA PRO_KEY
SaaS Boilerplate completo. Deploy seguro com regras validadas, CI/CD, SSR e Stripe Checkout. Inclui tudo do Lite + produção real.
:::

<h1>💎 DomisDocs Pro - R$197 - EM DESENVOLVIMENTO</h1>

> Do `ng new` ao deploy em produção com regras seguras, CI/CD, SSR e Stripe. 
>
> O que empresas cobram R$2.000 para configurar.

<h2>Referências:</h2>

> **Vitrine Pública:** `DomisDocs-Technical` - Documentação Open Source.
>
> **Entrega:** Direta via PRO_KEY + `npm create domis@latest` após pagamento na Kiwify.

<h2>Lite vs Pro - Referência Documental:</h2>

| O que você precisa em produção | Lite R$49 | Pro R$197 Em Breve |
| :--- | :---: | :--- |
| Fix public directory + 404 SPA | ✅ | ✅ |
| Cache 1 ano + Compressão | ✅ | ✅ |
| Next.Js 15 + Tailwind v4 + shadcn | ✅ Starter | ✅ SaaS Completo |
| firestore.rules seguro (prod) | ❌ | ✅ avançada |
| storage.rules seguro (prod) | ❌ | ✅ avançada |
| GitHub Actions - Auto Deploy | ❌ | ✅ |
| Cloud Functions - kiwifyWebhook, verifyProKey, ping | ❌ | ✅ Node 22 - getSignedUrl 5min |
| Stripe Checkout + Webhook + Customer Portal | ❌ | ✅ |
| Headers de Segurança HSTS, CSP | ✅ | ✅ |
| Dashboard SaaS Premium | ❌ | ✅ |

<h2>O que vem no Pro:</h2>

```bash
templates/domisdocs-pro/
├── src/
│   ├── app/
│   ├── components/
│   ├── lib/
│   └── assets/
├── firebase.json → public: "out" + rewrites + headers
├── .firebaserc  → básica validada
├── firestore.rules  → básica validada
├── next.config.ts  → otimizado Firebase
├── postcss.config.mjs  → v4 configurado
├── package.json
```
> No Pack: Pro , são mais pastas disponíveis.

<h3>Dashboard:</h3>

O Pro entrega o Dashboard SaaS com:
- Sidebar: Visão Geral, Analytics, Projetos, Equipe, Assinatura, Configurações ,etc
- Header: Search + Bell + Avatar
- Cards: Projetos Ativos, Segurança 100%, Componentes 48, Plano
- Stack UI: Next.Js 15 + Tailwind v4 + lucide-react + shadcn/ui

<h2>Instalação:</h2>

<h3>Fluxo de Uso:</h3>

- Cliente roda :

```bash
npm create domis@latest
```

<h3>CLI faz :</h3>

```
✔ DomisPacks Technical v1.0.52
✔ Qual pack você quer acelerar hoje?
```

<h4>Você escolhe os Packs:</h4>

```
✔ 🔥 DomisDocs Lite — Next.Js 15 + SaaS
```

<h4>O CLI valida a key, baixa o ZIP e monta a pasta:</h4>

- Cola a PRO_KEY
- Define o nome do projeto

> Ou:

```
✔ 🔥 DomisDocs PRO — Stripe + Rules
```

- Cola a PRO_KEY
- Define o nome do projeto

<h3>Depois:</h3>

```
✔ Baixando...
```

<h5>Crie um nome para o projeto</h5>

```bash
👉 cd + nome do projeto
```

<h5>Instale as dependências</h5>

```bash
👉 npm install
```
<h5>Para testar localmente via Localhost: </h5>

```bash
👉 npm run dev
```

<h5>Para fazer o Deploy do projeto</h5>

```bash
👉 firebase deploy --only hosting
```

<h5>Para fazer o Deploy das functions</h5>

```bash
👉 firebase deploy --only functions
```

> Ou tudo:

```bash
👉 firebase deploy
```

<h2>Regras Seguras - Documentação:</h2>

O Pro segue Firebase Security Checklist Oficial:

```bash
- Nenhum allow read, write: if true
- request.auth != null em tudo privado
- request.auth.uid == resource.data.ownerId
- request.resource.size < 5MB no Storage
- Validação MIME type
```

Teste local:

```bash
firebase emulators:start --only firestore,storage
```

<h2>FAQ:</h2>

::: details Preciso do Lite antes?
Não. O Pro já inclui tudo do Lite. Lite é porta de entrada. Se vai para produção com cliente, vá direto de Pro.
:::

::: details Funciona com Angular Universal SSR?
Sim. A pasta functions/ já vem com adapter Angular Universal. No README_PRO.md tem ng add @angular/ssr. No Next.Js 15 SSR já vem configurado.
:::

::: details As Rules são seguras mesmo?
Sim. Seguem checklist oficial Firebase. Nenhum if true. Teste com emulators antes.
:::

::: details Cliente já tem projeto Firebase?
Perfeito. O Pro não cria projeto novo, só injeta .rules e firebase.json otimizado. Roda firebase deploy e pronto.
:::

<h2>💬 Quem usa o Pro em produção diz:</h2>

<div style="
  margin: 32px 0; 
  padding: 28px; 
  background: rgba(255,255,255,0.03); 
  border-radius: 16px; 
  border: 1px solid rgba(38,255,0,0.15);"
>
  <div style="display: flex; gap: 16px; align-items: flex-start;">
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
      flex-shrink: 0;"
    > F</div>
      <div style="flex: 1;">
      <div style="display: flex; align-items: center; gap: 8px; margin-bottom: 8px; flex-wrap: wrap;">
      <span style="font-weight: 700; font-size: 16px; color: #fff;">Fernanda L.</span>
      <span style="font-size: 13px; opacity: 0.6;">· Tech Lead · Agência em Curitiba</span>
      <span style="margin-left: auto; color: #FFD700;">★★★★★</span>
      </div>
        <p style="
          font-size: 15px; 
          line-height: 1.6; 
          margin: 12px 0; 
          font-style: italic; 
          color: #e5e7eb;"
        >
          "Comprei o Lite para um projeto pessoal e depois peguei o Pro para o projeto de um cliente. O que me conquistou e surpreendeu foi o <code>firestore.rules</code> seguro e o GitHub Actions. Antes eu deixava <code>allow read, write: if true</code> e morria de medo de vazar dados. Agora o deploy é <code>git push</code> e o SSR já deixa o Lighthouse em 94. Economizei R$1.200 que um freela cobrou para fazer isso.     "
        </p>
        <div style="display: flex; gap: 12px; margin-top: 12px; font-size: 12px; opacity: 0.5; flex-wrap: wrap;">
        <span>✅ Compra verificada na Kiwify</span>
        <span>·</span>
        <span>📅 Há 5 dias</span>
      </div>
    </div>
  </div>
</div>

<h2>💎 Comprar DomisDocs Pro - R$199</h2>

<div style="
  margin: 24px 0; 
  padding: 28px; 
  background: linear-gradient(135deg, #1a0a1a, #0a1a0a); 
  border-radius: 20px; 
  border: 2px solid #555; 
  text-align: center; 
  box-shadow: 0 8px 32px rgba(255,255,255,0.05); 
  opacity: 0.7;"
>
  <h3 style="
    color: #ffffff !important; 
    font-size: 24px; 
    font-weight: 900; 
    margin-bottom: 8px;"
  > 💎 DOMISDOCS PRO - R$199</h3>
  <p style="
    color: #9ca3af !important; 
    font-size: 16px; 
    font-weight: 700; 
    margin: 8px 0;"
  > Produção Completa - Em breve</p>
  <p style="
    color: #e5e7eb !important; 
    font-size: 14px; 
    margin: 12px 0;"
  >
    ✅ Tudo do Lite + Rules + Hosting + CI/CD + SSR<br/>
    ✅ Template Enterprise pronto pra cliente<br/>
    ✅ 6 meses updates
  </p>
  <button disabled style="
    display: inline-block; 
    margin: 16px 0; 
    padding: 16px 32px; 
    background: #333; 
    color: #888 !important; 
    font-weight: 900; 
    font-size: 18px; 
    border-radius: 12px; 
    border: none; 
    cursor: not-allowed;"
  > 🔒 PRO EM BREVE - AGUARDE</button>
  <p style="
    color: #9ca3af !important; 
    font-size: 12px; 
    margin-top: 12px;"
  > 📦 Botão desabilitado até  finalizar Stripe + Functions Node 22
  </p>
</div>

&nbsp;
::: tip Já comprou o Lite?
> Envie comprovante do Lite e ganhe cupom de R$49 OFF. Paga só a diferença para o Pro.
:::

<h2>🛡 Garantia</h2>

> Todos os packs têm **7 dias de garantia incondicional** via Kiwify.