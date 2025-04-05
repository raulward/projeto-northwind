# Sumário Executivo – Projeto Northwind

## Visão Geral
Este projeto de análise de dados foi desenvolvido para fornecer uma visão integrada dos principais indicadores de performance da Northwind Traders. O foco é embasar decisões estratégicas que permitam aumentar o ticket médio e reduzir o churn, contribuindo para que a empresa se torne uma organização data driven.

## Contexto e Desafios
A Northwind Traders é uma empresa fictícia que atua nos setores de alimentos, bebidas e utilidades domésticas. Com aproximadamente 30 funcionários e um faturamento mensal de R$1,5 milhão, a empresa enfrenta desafios devido ao crescimento acelerado:
- **Relatórios Descentralizados:** Processos manuais e planilhas, que geram inconsistências e dificultam a tomada de decisão.
- **Necessidade de Integração de Dados:** Diversas fontes (ERP em PostgreSQL, CRM da Salesforce e sistema de contabilidade da ContaAzul) demandam uma unificação para análise abrangente.
- **Foco Estratégico:** A diretoria deseja aumentar o ticket médio e reduzir o churn (perda de clientes), essenciais para a sustentabilidade do negócio.

## Objetivos do Projeto
- **Integração e Limpeza de Dados:** Consolidar e tratar os dados extraídos de 14 tabelas do dataset Northwind.
- **Desenvolvimento de Indicadores:** Criar métricas chave como ticket médio (com remoção de outliers via IQR), taxa de churn (clientes inativos há mais de 60 dias), análise do comportamento dos pedidos e desempenho dos empregados.
- **Visualização Interativa:** Construir dashboards interativos no Power BI para facilitar a visualização dos insights e subsidiar a tomada de decisão.

## Principais Insights
- **Ticket Médio com Remoção de Outliers:** A análise permitiu identificar o ticket médio real, eliminando valores extremos que poderiam distorcer a interpretação dos dados.
- **Taxa de Churn:** Clientes que não realizaram compras há mais de 60 dias representam aproximadamente 24,72% a 26,97% do total, indicando a necessidade de estratégias de retenção.
- **Desempenho dos Empregados:** Segmentação dos funcionários em grupos (acima ou dentro da média e abaixo da média de pedidos) possibilitou identificar oportunidades de melhoria e treinamento.
- **Produto Mais Vendido:** Identificação dos produtos com maior volume de vendas, permitindo focar estratégias de marketing e reposicionamento de estoque.
- **Intervalo entre Compras:** Insights sobre o tempo médio que os clientes levam para realizar novas compras, auxiliando na definição de campanhas de reativação.

## Tecnologias Utilizadas
- **Python:** Utilizado para manipulação, limpeza e análise dos dados (bibliotecas como Pandas, NumPy e Matplotlib).
- **Jupyter Notebook:** Ambiente para desenvolvimento e documentação da análise de dados.
- **DAX e Power BI Desktop:** Criação de medidas, tabelas calculadas e dashboards interativos para visualização dos indicadores.
- **SQL (PostgreSQL):** Fonte dos dados do ERP da Northwind.

## Metodologia
1. **Coleta e Integração de Dados:** Importação dos dados do dataset Northwind, composto por 14 tabelas, e integração das informações.
2. **Análise Exploratória:** Identificação de padrões, outliers e inconsistências nos dados, utilizando técnicas estatísticas e visualizações.
3. **Desenvolvimento dos Indicadores:** Cálculo de métricas como ticket médio, churn, desempenho dos empregados e produtos mais vendidos.
4. **Visualização:** Criação de dashboards no Power BI para monitoramento dos principais indicadores e suporte à tomada de decisão.

## Conclusão
Através deste projeto, demonstramos que a integração e a análise aprofundada dos dados são essenciais para melhorar a performance operacional e comercial da Northwind Traders. Os insights obtidos permitem ações estratégicas que podem levar a um aumento do ticket médio, à redução do churn e à otimização dos processos internos. Este projeto serve como base para a transformação da empresa em uma organização orientada por dados, promovendo decisões mais rápidas e precisas.

## Contato
- **Nome:** Raul Ward
- **Email:** raulwarddev@gmail.com

## Links
- **Dashboard**: https://app.powerbi.com/groups/me/reports/648b7300-73d3-4302-856b-35accf9230ea?pbi_source=desktop
- **Github**: https://github.com/raulward/projeto-northwind
