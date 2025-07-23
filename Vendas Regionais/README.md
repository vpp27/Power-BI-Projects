# Primeira dashboard criada no Power BI.

Este projeto simula um cenário realista de uma empresa que realiza vendas em todo o Brasil, com dados fictícios estruturados para fins de treinamento e portfólio.
O objetivo foi criar um painel visual interativo que permitisse a análise do desempenho de vendas por estado, região, cliente, produto e período de tempo.


## Estrutura do Projeto

- **Base de Dados**: arquivo Excel com 4 abas (`Vendas`, `Clientes`, `Produtos`, `Regiões`)
- **Ferramentas Utilizadas**:
  - Power BI Desktop
  - Power Query (para tratamento de dados)
  - DAX (para cálculos e KPIs)
  - Excel (como fonte de dados)

## Visões e Métricas Apresentadas

### KPIs Principais
- Total de Pedidos
- Total de Itens Vendidos
- Total de Vendas (R$)
- Ticket Médio por Pedido

### Visualizações
- Vendas por Ano e Mês (linha do tempo)
- Vendas por Estado (gráfico de colunas)
- Vendas por Categoria de Produto (pizza)
- Top 10 Clientes por Faturamento (tabela)
- Produtos Mais Vendidos por Quantidade (tabela)

### Segmentações (Filtros)
- Região
- Estado
- Mês/Ano
- Cliente
- Categoria de Produto

## Principais Aprendizados

- Estruturação de modelo estrela com múltiplas tabelas relacionadas
- Uso de medidas DAX básicas (`SUMX`, `COUNTROWS`, cálculos de ticket médio)
- Boas práticas de visualização: layout limpo, KPIs no topo, segmentações à direita
- Aplicação de filtros Top N em visuais de tabela
- Design responsivo e intuitivo para análise exploratória

## Visual do Dashboard

![Dashboard de Vendas](./Dashboard)

## Arquivos

- `Desafio_PowerBI_Realista.pbix`: relatório Power BI final
- `Desafio_PowerBI_Realista.xlsx`: base de dados fictícia

## Próximos Passos (Ideias de Evolução)

- Comparação entre anos (crescimento YoY)
- Metas e indicadores de desempenho por estado
- Integração com dados públicos (ex: PIB regional ou população)

> Projeto desenvolvido como parte de estudos em Power BI no contexto do MBA em Data Science e Analytics.
