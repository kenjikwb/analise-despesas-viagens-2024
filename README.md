#Análise de Despesas com Viagens de Servidores Públicos (2024)
##📋 Sobre o Projeto
Este projeto realiza uma análise exploratória dos gastos com viagens de servidores públicos em 2024, utilizando dados públicos do Portal da Transparência. O objetivo é identificar quais cargos têm maior despesa média por viagem e entender padrões de deslocamento dentro da administração pública.

A análise filtra apenas cargos relevantes (com representatividade maior que 1% do total de viagens) para evitar distorções causadas por categorias com poucas amostras.

##🎯 Principais Insights
Despesa Média por Cargo: Identifica os cargos com maior gasto médio por viagem

Filtro de Relevância: Considera apenas categorias que representam mais de 1% do volume total de viagens

Visualização Clara: Gráfico de barras horizontal mostrando os top cargos por despesa

##🛠️ Tecnologias Utilizadas
Python 3.x

Pandas: Manipulação e análise de dados

Matplotlib: Visualização de gráficos

Jupyter Notebook: Ambiente de desenvolvimento interativo

##📊 Estrutura dos Dados
Os dados utilizados vêm do Portal da Transparência e contêm informações sobre:

Cargo do servidor

Data da viagem

Origem e destino

Valor da despesa

Outros detalhes administrativos

##🔍 Metodologia
Etapas da Análise:
Coleta de Dados: Extração dos dados do Portal da Transparência

Limpeza: Tratamento de valores faltantes e inconsistências

Filtragem: Seleção de cargos com >1% de representatividade no volume total

Cálculo de Médias: Despesa média por cargo dos cargos filtrados

Visualização: Gráfico de barras destacando os principais cargos
