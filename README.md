# Curso Power BI – Data Science Academy (DSA)

Este repositório reúne os projetos e laboratórios desenvolvidos durante o curso **Microsoft Power BI Para Business Intelligence e Data Science**, da Data Science Academy (DSA).

O objetivo é consolidar, na prática, conceitos fundamentais de:

- Business Intelligence  
- Modelagem de Dados  
- DAX  
- Visualização Analítica  
- Construção de Dashboards orientados a perguntas de negócio  

Todos os projetos foram desenvolvidos utilizando **Power BI Desktop**, com foco em transformar dados brutos em insights acionáveis para apoio à tomada de decisão.

---

## Estrutura do Repositório

- `Cap02_Primeiros_passos/`  
  Projeto prático de construção de um dashboard de vendas orientado a perguntas de negócio.  
  Inclui dataset, laboratório desenvolvido e documento com as perguntas estratégicas que guiaram a análise.

- `Cap03_Modelagem_relac_dax/`  
  Projeto focado em modelagem de dados, criação de relacionamentos e desenvolvimento de métricas utilizando DAX.  
  Inclui os datasets utilizados, laboratório prático e documento com as perguntas de negócio e metas definidas.

- `Cap04_Marketing/`  
  Mini-projeto de análise de dados de marketing com Power BI, explorando perfil de clientes, comportamento de compra e desempenho de campanhas.
  Inclui pasta para o Mini-Projeto 1, contendo o dataset utilizado e o arquivo do dashboard desenvolvido.

- `Cap05_Comercial/`  
  Mini-projeto de análise de dados comerciais e performance de vendas com Power BI, explorando performance de vendas por diferentes categorias, visual de Principais Influenciadores e distribuição geográfica de vendedores.
  Inclui o Mini-Projeto 2, contendo o dataset utilizado e o arquivo do dashboard desenvolvido.

- `Cap06_RH/`  
  Mini-projeto de análise de dados de recursos humanos com Power BI, explorando algumas características de funcionários de uma empresa fictícia.
  Inclui o Mini-Projeto 3, contendo o dataset utilizado, arquivo do dashboard desenvolvido e documento com as perguntas de négócio.

- `Cap07_Logistica/`  
  Mini-projeto de análise de dados de logística com Power BI.
  Inclui o Mini-Projeto 4, contendo o dataset utilizado, arquivo do dashboard disponibilizado a ser corrigido, arquivo do dashboard desenvolvido com as correções e documento com orientações do mini-projeto.


- `README.md`  
  Documento principal do repositório, contendo a descrição dos projetos, objetivos e organização geral do curso.

---

## Capítulo 02 – Primeiros Passos

Neste laboratório foi desenvolvido um **dashboard de vendas** com foco em responder perguntas estratégicas de negócio.

### Perguntas respondidas:

1. Qual o valor total vendido?  
2. Quantas vendas foram realizadas por categoria de produto?  
3. Quantas vendas foram realizadas por país considerando a prioridade de entrega?  
4. Qual foi a média de desconto nas vendas por subcategoria de produto?  
5. Quais países tiveram maior média de valor de venda? (visualização em mapa)

### Filtros disponíveis no dashboard:

- Ano  
- Segmento  
- País  

Este projeto foca na construção de visualizações claras, uso correto de segmentações e organização do relatório para exploração interativa dos dados.

Link: https://bit.ly/dsa_lab01

---

## Capítulo 03 – Modelagem, Relacionamentos e DAX

Neste laboratório o foco foi aprofundar conceitos de:

- Modelagem de dados  
- Relacionamentos entre tabelas  
- Criação de medidas com DAX  
- KPIs  
- Métricas de desempenho  

### Perguntas de negócio respondidas:

1. Total de valor de venda por modo de envio (gráfico de cascata)  
2. Mercados com maior custo médio de envio (treemap)  
3. Indicador KPI para média mensal de valor de venda (meta: 350)  
   - A empresa ficou acima ou abaixo da meta em Abril/2014?  
4. Categoria com maior lucro médio  
   - Lucro = Valor Venda - Custo Envio  
5. Comportamento da margem de lucro ao longo do tempo  
   - Margem = Lucro / Valor Venda  

Este módulo enfatiza análise orientada a metas, métricas financeiras e construção de indicadores de performance.

Link: https://bit.ly/dsa_lab2

---

## Capítulo 04 – Power BI para Análise de Dados - Marketing

Mini-Projeto desenvolvido com foco na análise de perfil de clientes, comportamento de compra e desempenho de campanhas de marketing.
O dashboard foi estruturado em quatro visões analíticas, explorando diferentes perspectivas da base de dados:

- **Visão Cliente**: perfil dos clientes, análise demográfica considerando escolaridade, estado civil e renda. Traz também informações sobre o volume de compras por canal. Esse painel permite compreender quem são os clientes da empresa e como características socioeconômicas se relacionam com o comportamento de compra.

- **Visão Comportamento**: análise de hábitos de compras dos clientes, relação entre renda, estrutura familiar, escolaridade e volume de gastos. Essa análise ajuda a identificar quais perfis de clientes tendem a gastar mais e quais fatores influenciam o consumo.

- **Visão Campanhas**: análise da performance das campanhas de marketing, com identificação de perfis com maior propensão de resposta às campanhas. Essa visão permite entender quais perfis de clientes respondem melhor às campanhas de marketing.

- **Visão Pontos de Venda**: análise de padrões de compra, comparação de gastos por categoria de produto e mercado. Essa visão fornece uma perspectiva geográfica e estratégica do comportamento de compra.

O projeto explora cruzamentos entre variáveis demográficas, econômicas e comportamentais para identificar padrões de consumo e oportunidades para estratégias de marketing.

Link: https://bit.ly/mini_projeto01

---

## Capítulo 05 – Power BI para Análise de Dados Comerciais

Mini-projeto desenvolvido com foco na análise de dados comerciais e performance de vendas.

O dashboard foi estruturado com ênfase em clareza e organização da informação, distribuindo as análises em diferentes painéis para facilitar a leitura e interpretação dos dados.

### Principais análises realizadas:

- Performance de vendas por **segmento, categoria e fabricante**
- Identificação de fatores que influenciam o valor de venda (Principais Influenciadores)
- Análise de distribuição de vendas por **loja e categoria**
- Visualização geográfica de vendedores com maior volume de vendas

O projeto reforça a importância de construir dashboards com foco em **comunicação eficiente**, evitando excesso de informações em uma única visualização e priorizando clareza na apresentação dos dados.

Observação: o visual de "Principais Influenciadores" não é compatível com a funcionalidade "Publicar na Web" do Power BI e, por isso, pode não estar disponível na versão online do dashboard.

Link: https://bit.ly/4uEfdJB

---

## Capítulo 06 – Power BI para Análise de Dados de Recursos Humanos

Mini-projeto desenvolvido com foco na análise de dados de Recursos Humanos (RH), explorando indicadores relacionados a perfil dos funcionários, experiência, remuneração e engajamento.

Durante o projeto foram utilizados recursos como criação de medidas, colunas condicionais e organização de métricas para análise de pessoas.

### Perguntas de negócio respondidas:

1. Qual o total de funcionários atualmente na empresa?  
2. Qual o tempo médio de experiência dos funcionários (em anos)?  
3. Qual o total e percentual de funcionários por gênero?  
4. Qual a média salarial mensal?  
5. Qual o total de funcionários por função?  
6. Qual o percentual de funcionários disponíveis para fazer hora extra?  
7. Qual o nível de envolvimento dos funcionários no trabalho (Ruim, Baixo, Médio e Alto)?  

### Análise adicional:

- Total e percentual de funcionários elegíveis para promoção  
  (considerando 5 anos ou mais desde a última promoção)

Este projeto foca na construção de indicadores de RH e análise de dados organizacionais, permitindo compreender a estrutura da empresa, o perfil dos colaboradores e possíveis ações relacionadas à gestão de pessoas.

Link: https://bit.ly/3QtXm8Q

---

## Capítulo 07 – Power BI para Análise de Dados de Logística

Em desenvolvimento.

---

## Tecnologias Utilizadas

- Power BI Desktop  
- Modelagem relacional  
- DAX  
- Visualizações interativas  

---

## Objetivo do Repositório

Este repositório funciona como:

- Registro prático da evolução no curso  
- Portfólio de projetos em Business Intelligence  
- Demonstração de organização, modelagem e pensamento analítico  