![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Análise de clientes

Nesse exercício, vamos usar o arquivo `marketing_customer_analysis.csv` dentro da pasta `files_for_lab`.

Vamos fazer os mesmos passos do exercício anterior, adicionando o passo de tunagem de hiperparametros do modelo. Você pode modificar o mesmo arquivo criado no lab anterior.

### 01 - Problema 

- Quais são as colunas dessa tabela? Temos problemas de correlação, variância ou cardinalidade?
- Seu objetivo é prever a coluna Total Claim Amount.

### 02 - Importando dados

- Ler o arquivo `.csv`.

### 03 - Limpeza/Manipulação/Análise de dados exploratória

- Mude o nome das colunas
- Análise variáveis númericas.
- Explore os dados para encontrar padrões.

### 04 - Processamento

- Lide com valores nulos.
- Lide com variáveis categóricas.
- Corrija a variável de data
- Lide com outliers.
- Deixe as variáveis na mesma escala.
- Separe treino e teste.

### 05 - Modelagem

- Aplique o modelo.

### 06 - Validação de modelo

- R2.
- MSE.
- RMSE.
- MAE.
### 07 - Feature Selection


- Aplique a técnica de variance treshold no modelo, quais colunas foram eliminadas? O que aconteceu com a nota do modelo após a eliminação de colunas?

- Aplique a técnica de Recursive Feature Elimination no modelo, quais colunas foram eliminadas? O que aconteceu com a nota do modelo após a eliminação de colunas?

### 08 - Tunagem de hyperparametros
- Use o grid search para buscar os melhores hyperparametros tanto para o modelo de boosting quanto para o modelo de random forest. Houve alguma melhora nas métricas do modelo?
 
### 09 - Pipelines
- Quais tratamentos podem ser modificados para funções do sklearn e colocados em uma pipeline? Crie uma pipeline para modelagem de customers
- Para fazer esses tratamentos quais argumentos do pycaret devem ser utilizados? Qual é o melhor r2 obtido pelo pycaret?

### 10 - Relatório
- Apresente os resultados.
