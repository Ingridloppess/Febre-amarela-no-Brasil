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

### 1. Total de casos de 1994 até 2023
Gráfico de linha exibindo a quantidade de casos ao longo dos anos.
![IMG_PJ_Bigdata(2)](https://github.com/user-attachments/assets/e435fead-5173-46eb-97c3-b90e1edb9003)

### 2. Distribuição dos Casos por Sexo
Gráfico de pizza mostrando a proporção de casos por sexo, indicando se a febre amarela afetou mais homens ou mulheres no período analisado.
![img big data (4)](https://github.com/user-attachments/assets/97b11c61-692d-420c-aa99-4cf0db2d29b0)

### 3. Quatidade de casos por ano
Gráfico de barras mostrando a quantidade de casos por ano, destacando anos de maior incidência.
![img big data (5)](https://github.com/user-attachments/assets/da1c6b6e-e3b2-4ce7-87c6-0c56894bf36f)

### 4. Distribuição de Idades
Histograma mostrando a frequência de casos em diferentes faixas etárias, indicando quais idades foram mais afetadas.
![BIGDATA(6)](https://github.com/user-attachments/assets/8e9b1310-60e7-4019-9965-9a5fc04b97ad)

### 5. Evolução Temporal dos Casos (Ano e Mês)
Gráfico de linha detalhando a quantidade de casos por mês e ano.
![BIG DATA (7)](https://github.com/user-attachments/assets/d6f61279-c09f-4d59-b32e-8b5a0820496d)

### 6. Óbitos vs Sobreviventes por Estado
Gráfico de barras empilhadas comparando o número de óbitos e sobreviventes por estado.
![download](https://github.com/user-attachments/assets/99791daa-a023-4cb0-b2a9-40efa82a3bd5)

### 7. Boxplot de Idades por Sexo
Gráfico boxplot comparando a distribuição de idades entre homens e mulheres, facilitando a análise de tendências demográficas entre os afetados.
![img big data(8)](https://github.com/user-attachments/assets/feafdf1b-3496-4f58-8dd2-6fc1efadbef6)

### 8. Casos Confirmados de Febre Amarela por estado e ano
Esse gráfico de barras empilhadas mostra o número total de casos confirmados de febre amarela em cada estado ao longo dos anos. Cada barra representa um estado, com diferentes cores dentro da barra indicando os casos ocorridos em diferentes anos.
![img big data (9)](https://github.com/user-attachments/assets/f2aefb6d-902a-4ed1-84b6-5404d850a29f)


## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Ingridloppess/Febre-amarela-no-Brasil

2. Abra o Google Colab e faça o upload do notebook.

3. Baixe o arquivo de dados casos_94_23.csve faça o upload no ambiente Colab.
   
4. Execute as células do notebook para reproduzir as análises e visualizações.
## Resultados

Com as análises elaboradas, foram obtidos insights relevantes:

Anos com maior incidência de febre amarela
Diferenças significativas na distribuição de casos entre homens e mulheres
Faixas etárias mais afetadas, diminuição possível vulnerabilidade específica
Estados com índices de mortalidade entre os maiores casos confirmados

## Licença
Este projeto está licenciado sob uma licença do MIT .

Nota : Os gráficos foram desenvolvidos com base em dados reais de saúde pública. Recomenda-se o uso responsável das informações e respeito aos dados sensíveis envolvidos.
