# Análise de Despesas com Viagens de Servidores Públicos (2024)
## 📋 Sobre o Projeto
Este projeto realiza uma análise exploratória dos gastos com viagens de servidores públicos em 2024, utilizando dados públicos do **Portal da Transparência**. Foi desenvolvido como parte do **curso de Python para Análise de Dados da Asimov Academy**, aplicando técnicas profissionais de limpeza, transformação e visualização de dados em um cenário real.

O objetivo é identificar padrões de deslocamento e despesas na administração pública, demonstrando domínio em ferramentas como Pandas e Matplotlib. A análise filtra apenas cargos **relevantes** (com representatividade maior que 1% do total de viagens) para garantir insights baseados em dados significativos

## 🎯 Principais Insights
**Despesa Média por Cargo:** Identifica os cargos com maior gasto médio por viagem

**Filtro de Relevância:** Considera apenas categorias que representam mais de 1% do volume total de viagens

**Visualização Clara:** Gráfico de barras horizontal mostrando os top cargos por despesa

## 🛠️ Tecnologias Utilizadas
**Python 3.x**

**Pandas:** Manipulação, transformação e agregação de dados

**Matplotlib:** Visualização de gráficos

**Jupyter Notebook:** Ambiente de desenvolvimento interativo

## 📊 Estrutura dos Dados
Os dados utilizados vêm do Portal da Transparência e contêm informações sobre:

- Cargo do servidor

- Período de viagem (data de início e fim)

- Origem e destino

- Valor da despesa (diárias, passagens, outros gastos)

- Outros detalhes administrativos

## 🔍 Metodologia
**Etapas da Análise:**

**1. Coleta de Dados:** Extração dos dados do Portal da Transparência

**2. Limpeza:** Tratamento de valores faltantes e inconsistências

**3. Filtragem:** Seleção de cargos com >1% de representatividade no volume total

**4. Cálculo de Médias:** Despesa média por cargo dos cargos filtrados

**5. Visualização:** Gráfico de barras destacando os principais cargos

## Obtendo os Dados
Os dados brutos utilizados neste projeto são públicos e podem ser obtidos diretamente do Portal da Transparência do governo federal:

[Portal da Transparência - Dados de Viagens](https://portaldatransparencia.gov.br/download-de-dados/viagens)
