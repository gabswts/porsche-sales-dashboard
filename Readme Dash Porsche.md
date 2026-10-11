# 🏎️ Porsche Sales Intelligence Dashboard

Dashboard interativa em arquivo único HTML desenvolvida para responder a perguntas estratégicas de negócio sobre a base de dados de 100 vendas de veículos Porsche, criada no âmbito do **Curso Criando Agentes de Tratamento de Dados** ministrado pelo expert **Felipe Aguiar (Felipão)**.

## 📌 Contexto & Desafio
Em vendas de alto padrão, dados não sanitizados (com inconsistências de moeda, datas inválidas, nomes despadronizados e textos truncados) impedem a geração de relatórios de BI confiáveis. 

Esta aplicação demonstra na prática como um **Agente Inteligente de Tratamento de Dados** transforma um "dado cru/sujo" em uma interface limpa, dinâmica e focada na tomada de decisão.

## 🎯 Perguntas de Negócio Respondidas
1. **Financeiro:** Qual método de pagamento gera maior faturamento e volume?
2. **Geográfico:** Quais Estados concentram o maior volume de receita?
3. **Safra do Veículo:** Como o ano do modelo impacta o ticket médio de venda?

## 🚀 Funcionalidades da Dashboard
- **KPIs em Tempo Real:** Receita Total, Volume de Unidades, Ticket Médio e Quilometragem Média.
- **Gráficos Interativos (Chart.js):**
  - Gráfico de Barras para faturamento por canal de pagamento.
  - Gráfico Donut para distribuição percentual por Estado.
  - Gráfico de Linha/Área para evolução do ticket médio por ano do modelo.
- **Filtros Dinâmicos Cruzados:** Recorte por Método de Pagamento, Estado (UF), Ano e Status de Entrega, além de barra de pesquisa textual.
- **Modo Comparativo (Cru vs. Sanitizado):** Alternador no cabeçalho que permite visualizar em tempo real a diferença entre a tabela crua (dados não tratados) e a limpa.

## 🛠️ Tecnologias Utilizadas
- **HTML5 & JavaScript (ES6+):** Estrutura e lógica de manipulação de arrays sem dependências pesadas de backend.
- **Tailwind CSS (CDN):** Estilização moderna e responsiva baseada no tema Dark / Porsche Red.
- **Chart.js (CDN):** Renderização visual dos dados e tooltips dinâmicos.
- **FontAwesome:** Iconografia corporativa.

## 📂 Como Executar
1. Faça o download ou clone este repositório.
2. Abra o arquivo `dashboard_porsche.html` diretamente em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
3. Não requer instalação de servidores ou bibliotecas locais (`Node.js`, `Python`, etc.).