# Global Market Radar

**Radar de Oportunidade de Mercado** — cotação de Bitcoin (BTC), USD/BRL, score de oportunidade, notícias e calculadora em tempo real.

---

## 🚀 Sobre o projeto

O **Global Market Radar** é uma ferramenta web de análise de mercado financeiro focada em:

- Cotação **Bitcoin (BTC/USD)** em tempo real
- Cotação **USD/BRL** (dólar)
- **Score de oportunidade** de compra (0–100)
- **Drivers** que explicam o que está puxando o score
- **Calculadora de Bitcoin** (preço × quantidade → valor em USD e R$)
- **Notícias** relevantes do mercado (Fed, geopolítica, commodities, BTC)
- Tema visual dinâmico (verde para dólar / laranja para Bitcoin)

---

## ✨ Funcionalidades

| Recurso | Descrição |
|---------|-----------|
| **Cotações ao vivo** | Dados da Open Exchange Rates e CoinGecko |
| **Score de oportunidade** | Indicador visual + sinal COMPRAR / AGUARDAR / EVITAR |
| **Drivers** | 5 fatores principais que influenciam o score (atualizam conforme o ativo) |
| **Calculadora BTC** | Preço editável + quantidade → total em USD e R$ |
| **Notícias** | Feed automático via Google News (RSS) |
| **Tema BTC** | Interface muda para laranja ao selecionar Bitcoin |
| **Responsivo** | Funciona bem em desktop e mobile |

---

## 🔍 SEO

O site já está preparado para indexação com:

- Title e Meta Description otimizados
- Keywords relevantes (bitcoin, cotação btc, usd brl, score de oportunidade, etc.)
- Open Graph + Twitter Cards
- JSON-LD (Schema.org – WebApplication / FinanceApplication)
- Canonical, robots e alt texts nas imagens

**Principais palavras-chave:**
`bitcoin`, `preço bitcoin`, `cotação btc`, `btc hoje`, `usd brl`, `dólar hoje`, `score de oportunidade`, `calculadora bitcoin`, `notícias bitcoin`, `criptomoedas`, `radar de mercado`

---

## 📂 Estrutura

```
.
├── index.html      # Aplicação completa (HTML + CSS + JS)
└── README.md       # Este arquivo
```

Tudo está em um único arquivo `index.html` (sem dependências externas de build).

---

## 🛠️ Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno  
   **ou**
2. Hospede em qualquer servidor estático (Netlify, Vercel, GitHub Pages, etc.)

**Recomendado:** use HTTPS para as APIs funcionarem corretamente.

### APIs utilizadas

| Serviço | Uso |
|---------|-----|
| [Open Exchange Rates](https://open.er-api.com) | Cotação USD → BRL |
| [CoinGecko](https://www.coingecko.com/api) | Preço do Bitcoin + variação 24h |
| [rss2json](https://rss2json.com) + Google News | Notícias de mercado |

---

## 📱 Tecnologias

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis de tema)
- JavaScript vanilla (Fetch API)
- Sem frameworks / sem build step

---

## ⚠️ Aviso

Este projeto é uma ferramenta de **análise e acompanhamento de mercado**.  
Não constitui recomendação de investimento. Sempre faça sua própria pesquisa.

---

## 📄 Licença

Uso livre para fins educacionais e pessoais.  
© 2026 Global Market Radar
