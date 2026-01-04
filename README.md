# 📊 Análise de Vendas – Power BI

## 🎯 Objetivo do Projeto
Este projeto tem como objetivo analisar o desempenho de vendas de uma empresa fictícia, explorando indicadores financeiros e comerciais para apoiar a tomada de decisão.  
O dashboard foi desenvolvido com foco em **clareza, boas práticas de visualização e KPIs executivos**.

---

## 🛠️ Ferramentas Utilizadas
- Power BI Desktop
- Excel (tratamento e entendimento dos dados)
- GitHub (versionamento e portfólio)

---

## 📁 Fonte dos Dados
- Dataset público **Sample Superstore**
- Dados de vendas contendo informações de pedidos, produtos, regiões e clientes

---

## 🧹 Tratamento de Dados
As seguintes etapas de tratamento foram realizadas:
- Ajuste de colunas de data utilizando localidade `en-US`
- Correção dos tipos de dados:
  - Valores financeiros como número decimal
  - Quantidade como número inteiro
- Remoção de colunas sem valor analítico (IDs e código postal)

---

## 📈 Indicadores Criados
- **Total de Vendas**
- **Total de Lucro**
- **Margem de Lucro (%)**
- **Quantidade Vendida**
- **Ticket Médio**

As métricas foram criadas utilizando **medidas DAX**, permitindo análise dinâmica por filtros e período.

---

## 📊 Dashboard
O dashboard apresenta:
- Visão geral de KPIs
- Vendas por categoria
- Evolução das vendas ao longo do tempo
- Lucro por subcategoria
- Segmentações por região, segmento e período

![Dashboard](imagens/dashboard.png)

---

## 💡 Principais Insights
- Algumas categorias apresentam alto volume de vendas, mas margem de lucro menor
- Determinadas subcategorias geram prejuízo recorrente
- O desempenho de vendas varia significativamente entre regiões
- O uso de descontos impacta diretamente o lucro final

---

## 📌 Observações
- O arquivo `.pbix` está disponível no repositório para análise detalhada
- Este projeto faz parte de um portfólio pessoal voltado para oportunidades como **Analista de Dados Júnior**

---

## 👤 Autor
Projeto desenvolvido para fins de estudo e portfólio.
