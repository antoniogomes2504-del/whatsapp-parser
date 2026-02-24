# 💼 VP Benefit Tracker

![Version](https://img.shields.io/badge/version-1.0-25D366?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![No Backend](https://img.shields.io/badge/backend-none-orange?style=for-the-badge)

> Controle o benefício anual de viagens interpretando conversas do WhatsApp com IA — 100% no browser.

🔗 **[Acessar online](https://antoniogomes2504-del.github.io/whatsapp-parser/)**

---

## ✨ O que faz

1. Você faz upload do `.txt` exportado do WhatsApp
2. A IA (Claude) interpreta a conversa em linguagem natural
3. Extrai automaticamente gastos, saldos, reembolsos e cancelamentos
4. Exibe um dashboard visual por beneficiário
5. Exporta relatório Excel profissional com 3 abas

---

## 🚀 Como Usar

1. Acesse o app pelo link acima
2. Insira sua chave da API [Anthropic Claude](https://console.anthropic.com/)
3. Arraste ou selecione o `.txt` exportado do WhatsApp
4. Clique em **Analisar Conversa com IA**
5. Visualize o dashboard e baixe o Excel

---

## 📊 Funcionalidades

- 🧠 **IA Claude** — interpreta linguagem natural das mensagens
- 📁 **Drag & Drop** — arraste o arquivo `.txt` direto no app
- 💰 **Dashboard** — cards de resumo + detalhamento por beneficiário
- 📈 **Barras de uso** — verde (normal), amarelo (atenção), vermelho (crítico)
- 📋 **Tabela de eventos** — expandível por beneficiário
- 📗 **Excel com 3 abas** — Dashboard, Eventos e Por Mês
- 🔒 **Privacidade** — dados processados no browser, nunca armazenados

---

## 🛠️ Tecnologias

| Tech | Uso |
|------|-----|
| React 18 | Interface e componentes |
| Tailwind CSS | Estilização |
| SheetJS (xlsx) | Geração do Excel |
| Anthropic Claude API | Interpretação da conversa |

---

## 📂 Estrutura

```
whatsapp-parser/
├── index.html                      # Aplicação principal
├── examples/
│   └── teste_vp_tracker.txt        # Conversa de exemplo
├── legacy/
│   └── Estruturar_conversa_do_WhatsApp.py  # Versão anterior (Python)
├── .gitignore
├── README.md
└── LICENSE
```

## 📄 Licença

MIT © 2026
