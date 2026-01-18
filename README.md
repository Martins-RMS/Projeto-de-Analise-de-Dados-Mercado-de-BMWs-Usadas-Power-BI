# Análise do Mercado de BMWs Usadas – Power BI

## Visão Geral
Este projeto consiste em uma análise exploratória e analítica do mercado de **BMWs usadas**, com o objetivo de identificar **quais modelos oferecem o melhor custo-benefício para permanecer no mercado de revenda**.

O projeto foi **proposto e desenvolvido de forma totalmente autoral**, desde a definição da pergunta de negócio até a construção das métricas e dashboards no Power BI.

---

## Pergunta de Negócio
**Quais modelos de BMW oferecem o melhor custo-benefício no mercado de usados, considerando preço, quilometragem, eficiência e características técnicas?**

---

## Base de Dados
- Formato: CSV  
- Tipo de dados:
  - Modelo
  - Ano
  - Preço
  - Quilometragem (milhas)
  - Eficiência (MPG)
  - Tipo de combustível
  - Tipo de transmissão

---

## Etapas do Projeto

### 1️⃣ ETL (Power Query)
- Importação da base CSV
- Tratamento de dados nulos
- Padronização de colunas
- Ajuste de tipos de dados
- Criação de colunas auxiliares (ex: milhas por ano)

 Processo realizado diretamente no Power BI.

---

### 2️⃣ Modelagem de Dados
- Modelo simples em **tabela única**, adequado ao escopo do projeto
- Garantia de consistência para uso das métricas DAX

---

### 3️⃣ Métricas e KPIs (DAX)

**KPIs principais:**
- Quantidade de modelos distintos
- Preço médio de venda
- Média de milhas rodadas
- Índice de Custo-Benefício

**Métricas criadas:**
- Preço médio
- Média de quilometragem
- Média de milhas rodadas por ano
- Eficiência média
- Rankings por preço, eficiência e quilometragem

---

### Índice de Custo-Benefício
Foi criado um **índice autoral** para ranquear os modelos de BMW com base em múltiplos fatores:

- Preço de venda
- Quilometragem
- Eficiência de combustível
- Comparação com a média do mercado

O índice consolida essas variáveis em **um único valor numérico**, facilitando a identificação dos modelos que oferecem maior valor pelo preço.

---

## Dashboards Desenvolvidos

### 🔹 Visão Geral do Mercado
- KPIs principais
- Modelos com melhor eficiência
- Distribuição por tipo de transmissão
- Modelos com menor média de preço
- Relação entre quilometragem máxima e média
- Evolução do preço médio por ano

### 🔹 Análise de Custo-Benefício
- Ranking de modelos pelo Índice de Custo-Benefício
- Comparação entre preço, eficiência e quilometragem
- Identificação de outliers e modelos menos vantajosos

![Visão Geral do Mercado](imagens/visao_geral.png)
![Análise de Custo-Benefício](imagens/relacoes.png)

---

## Principais Insights
- Modelos com preço intermediário e boa eficiência tendem a apresentar melhor custo-benefício.
- Veículos muito baratos geralmente possuem quilometragem elevada.
- Modelos mais novos nem sempre justificam o preço mais alto em relação ao benefício entregue.
- A eficiência de combustível tem forte impacto no valor percebido do veículo usado.

---

## Ferramentas Utilizadas
- Power BI
- Power Query
- DAX

---

## Autor

Projeto desenvolvido de forma **100% autoral**, com foco em análise de dados e tomada de decisão baseada em indicadores.
