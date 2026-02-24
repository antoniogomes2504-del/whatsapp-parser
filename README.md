# 💬 WhatsApp Tools — Parser & VP Benefit Tracker

![Version](https://img.shields.io/badge/version-3.0-25D366?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![No Backend](https://img.shields.io/badge/backend-none-orange?style=for-the-badge)

> Ferramentas web para processar conversas exportadas do WhatsApp — 100% no browser.

---

## 📱 App 1 — WhatsApp Parser

**Arquivo:** [`index.html`](index.html)

Parse conversas exportadas do WhatsApp e gere relatórios Excel formatados com 3 abas.

🔗 **[Acessar online](https://antoniogomes2504-del.github.io/whatsapp-parser/)**

### Features
- 📁 Drag & Drop de arquivo `.txt`
- 🔍 Parser inteligente de mensagens
- 📊 Excel com 3 abas (Conversa, Resumo, Por Dia)
- 🎨 Interface dark theme estilo WhatsApp

---

## 💼 App 2 — VP Benefit Tracker

**Arquivo:** [`vp-benefit-tracker.html`](vp-benefit-tracker.html)

Gerencie o benefício anual de viagens (R$60.000/VP) interpretando conversas WhatsApp com IA.

🔗 **[Acessar online](https://antoniogomes2504-del.github.io/whatsapp-parser/vp-benefit-tracker.html)**

### Features
- 🧠 IA (Claude API) interpreta linguagem natural
- 📊 Dashboard por VP com barras de utilização
- 🚨 Alertas visuais: Normal / Atenção / Crítico
- 💰 Controle de orçamento com saldo em tempo real
- 📗 Exportação Excel com 3 abas (Dashboard, Eventos, Por Mês)

### Pré-requisito
- Chave da API [Anthropic Claude](https://console.anthropic.com/) (armazenada localmente no browser)

---

## 🛠️ Tecnologias

| Tech | Uso |
|------|-----|
| React 18 | Interface e componentes |
| Tailwind CSS | Estilização |
| SheetJS (xlsx) | Geração do Excel |
| Anthropic Claude API | IA para interpretar mensagens (VP Tracker) |

## 📂 Estrutura

```
whatsapp-parser/
├── index.html                  # WhatsApp Parser (SPA)
├── vp-benefit-tracker.html     # VP Benefit Tracker (SPA)
├── teste_whatsapp.txt          # Arquivo de teste - Parser
├── teste_vp_tracker.txt        # Arquivo de teste - VP Tracker
├── README.md
├── LICENSE
└── .gitignore
```

## 📄 Licença

MIT © 2026
