# Titanic_Survival_Prediction

## Objetivo
Desenvolver um modelo de aprendizado de máquina (AM) para apoiar no processo de tomada de decisão, utilizando um dataset disponível no Kaggle. A tarefa inclui comparar os resultados obtidos com um estudo existente (Estudo X) que aplicou técnicas de AM ao mesmo dataset.

## Etapas

### 1. Seleção do Dataset:

A equipe deve escolher um dataset relevante e com dados suficientemente ricos para a aplicação das técnicas de AM. O Kaggle é uma excelente fonte para encontrar datasets de diversas áreas como saúde, finanças, marketing, entre outros.


### 2. Análise Estatística Descritiva

Realizar uma análise exploratória dos dados (EDA) para entender melhor as características do dataset.
Tarefas a realizar:
Calcular medidas descritivas (média, mediana, desvio padrão, etc.).
Visualizar a distribuição dos dados por meio de histogramas, boxplots, etc.
Identificar possíveis outliers.
Analisar correlações entre as variáveis (utilizar uma matriz de correlação, heatmaps).


### 3. Pré-processamento de Dados

Antes de aplicar qualquer técnica de AM, é essencial preparar os dados.
Tarefas a realizar:
Tratar valores ausentes (imputação ou remoção).
Normalizar ou padronizar os dados, se necessário.
Codificar variáveis categóricas (one-hot encoding, label encoding).
Dividir o dataset em conjuntos de treino e teste.


### 4. Treinamento e Teste com Cross-Validation

Aplicar cross-validation com k-folds para garantir que o modelo seja robusto e que os resultados não estejam enviesados.
Tarefas a realizar:
Escolher o número de folds (geralmente 5 ou 10).
Treinar o modelo com cada técnica de AM, garantindo que cada fold seja utilizado tanto para treino quanto para teste.


### 5. Implementação de Técnicas de AM

Implementar duas técnicas de AM diferentes das utilizadas no Estudo X.
Tarefas a realizar:
Se utilizar de bibliotecas ou softwares como Scikit-learn, R, ou KNIME.
Testar e validar os modelos implementados.


### 6. Parametrização com Grid Search

Usar grid search para otimizar os hiperparâmetros dos modelos, garantindo que a melhor versão de cada modelo seja utilizada.
Tarefas a realizar:
Definir o espaço de busca para cada hiperparâmetro.
Executar o grid search para encontrar a combinação de parâmetros que maximiza a performance do modelo.


### 7. Avaliação dos Modelos

Comparar os resultados obtidos pelas duas técnicas de AM com os resultados do Estudo X.
Tarefas a realizar:
Calcular métricas de desempenho (ex.: acurácia, precisão, recall, F1-score, AUC-ROC).
Criar gráficos comparativos entre os modelos desenvolvidos e o Estudo X.
