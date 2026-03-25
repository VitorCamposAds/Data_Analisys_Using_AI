# ☕ Coffee Shop — Network Health Dashboard

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chart.js&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

> Dashboard interativo de análise de saúde de rede para uma cafeteria com 3 unidades, cobrindo 149.116 transações no período de Janeiro a Junho de 2023.

---

## 📊 Visão Geral

Este projeto é um **dashboard analítico single-page** desenvolvido com HTML, CSS puro e Chart.js. Ele transforma dados transacionais de uma rede de coffee shops em visualizações interativas e insights acionáveis — sem nenhum framework ou dependência de backend.

**Período analisado:** Janeiro – Junho 2023  
**Lojas:** 3 unidades (Astoria, Hell's Kitchen, Lower Manhattan)  
**Transações:** 149.116  
**Receita Total:** $698,8k  

---

## 🗂️ Estrutura do Dashboard

O dashboard é organizado em **5 abas temáticas**:

| Aba | Conteúdo |
|---|---|
| 📊 **Visão Geral** | KPIs consolidados, evolução de receita, crescimento MoM |
| 🏪 **Lojas** | Comparativo de receita, volume e ticket médio por unidade |
| 🛍️ **Produtos** | Mix de categorias, top 10 produtos, receita por categoria |
| ⏰ **Comportamento** | Receita por hora do dia e dia da semana |
| 🚀 **Alavancas** | Matriz de oportunidades ranqueada por impacto e facilidade |

---

## ✨ Funcionalidades

- ⚡ **Zero dependências de backend** — arquivo HTML único, abre direto no browser
- 📱 **Responsivo** — layout adaptável para mobile e desktop
- 🌙 **Dark mode nativo** — tema escuro com paleta de cores consistente
- 📈 **10+ gráficos interativos** via Chart.js (linha, barra, doughnut)
- 🎨 **Design system próprio** com variáveis CSS e componentes reutilizáveis
- 💡 **Insight cards** contextualizando cada visualização
- 🏆 **Tabela de alavancas** com priorização por impacto estimado

---

## 🚀 Como Usar

**Opção 1 — Direto no Browser**

    git clone https://github.com/seu-usuario/coffee-shop-dashboard.git
    open index.html

**Opção 2 — Servidor Local (Python)**

    python -m http.server 8080

**Opção 2 — Servidor Local (Node.js)**

    npx serve .

Acesse `http://localhost:8080` no browser.

---

## 📁 Estrutura do Projeto

    coffee-shop-dashboard/
    │
    ├── index.html        # Dashboard completo (single-file)
    ├── README.md         # Este arquivo
    └── preview.png       # Screenshot do dashboard (opcional)

> Todo o CSS e JavaScript estão embutidos no `index.html` para facilitar o compartilhamento e deploy sem configuração adicional.

---

## 📌 Principais Insights

- 📈 **+103,8% de crescimento** de receita entre Janeiro e Junho
- ⏰ **46% da receita diária** concentrada entre 7h e 10h (Morning Rush)
- 🏪 **Diferença de apenas 2,8%** entre a melhor e pior loja — rede equilibrada
- ☕ **Coffee representa 38,6%** da receita total; Espresso é o produto #1 com $91,4k
- 🥐 **Bakery + cross-sell** identificado como maior alavanca de curto prazo

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura e markup semântico |
| **CSS3** | Estilização com variáveis, grid e flexbox |
| **JavaScript (ES6+)** | Lógica de tabs e inicialização dos gráficos |
| **[Chart.js 4.4.0](https://www.chartjs.org/)** | Renderização de gráficos via CDN |

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja `LICENSE` para mais informações.

---

## 🙋 Autor

Feito com ☕ por **[Vitor Campos](https://github.com/seu-usuario)**  
📍 Contagem, Minas Gerais, Brasil
