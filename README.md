# Análise de Casos de Febre Amarela no Brasil (1994 - 2023)

Este projeto, desenvolvido como parte do curso de Big Data em Python, realiza uma análise exploratória de dados sobre os casos de febre amarela no Brasil entre os anos de 1994 e 2023. Utilizando a biblioteca `pandas` para manipulação de dados e `matplotlib` para visualização, foram criados gráficos para entender melhor a distribuição dos casos ao longo dos anos, considerando variáveis como sexo, idade, e localização geográfica.

## Objetivo

Explorar os dados de febre amarela no Brasil para identificar padrões temporais e demográficos, incluindo:
- Total de casos confirmados ao longo dos anos
- Distribuição de casos por sexo
- Faixa etária mais afetada
- Padrões temporais e regionais na ocorrência dos casos
- Taxa de óbitos por estado

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal do projeto
- **Google Colab**: Ambiente de desenvolvimento utilizado
- **Bibliotecas**:
  - `pandas`: Para manipulação e limpeza de dados
  - `matplotlib`: Para criação de gráficos
  - `seaborn`: Para visualizações mais detalhadas

## Dados

O projeto utiliza dados em formato CSV, contendo as seguintes colunas principais:
- `SEXO`: Sexo do paciente (Feminino ou Masculino)
- `IDADE`: Idade do paciente
- `ANO_IS`, `MES_IS`: Ano e mês do caso registrado
- `UF_LPI`: Unidade Federativa (estado)
- `OBITO`: Indicação de óbito (sim ou não)

## Análises Realizadas

### 1. Evolução Temporal dos Casos
Gráfico de linha exibindo a quantidade de casos ao longo dos anos. Esta análise ajuda a identificar picos de incidência e possíveis surtos.

### 2. Distribuição dos Casos por Sexo
Gráfico de pizza mostrando a proporção de casos por sexo, indicando se a febre amarela afetou mais homens ou mulheres no período analisado.

### 3. Distribuição de Idades
Histograma exibindo a distribuição etária dos casos confirmados, o que permite observar faixas etárias mais afetadas.

### 4. Casos por Estado (Óbitos vs Sobreviventes)
Gráfico de barras empilhadas por estado, separando casos que resultaram em óbitos e casos onde o paciente sobreviveu, permitindo uma visão da severidade da doença em cada unidade federativa.

### 5. Boxplot de Idades por Sexo
Gráfico boxplot comparando a distribuição de idades entre homens e mulheres, facilitando a análise de tendências demográficas entre os afetados.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Ingridloppess/Febre-amarela-no-Brasil
