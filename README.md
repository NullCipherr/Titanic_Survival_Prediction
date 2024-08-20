# 🚢 Titanic Survival Prediction

## 🎯 Objetivo
Desenvolver um modelo de aprendizado de máquina (AM) para apoiar na tomada de decisão, utilizando um [dataset disponível no Kaggle](https://www.kaggle.com/c/titanic). O projeto inclui a comparação dos resultados obtidos com um estudo existente, chamado **Estudo X**, que aplicou técnicas de AM ao mesmo dataset.

## 🚀 Etapas

### 1. 🗂️ Seleção do Dataset
Escolha um dataset relevante e com dados ricos para aplicar técnicas de AM. O [Kaggle](https://www.kaggle.com/datasets) é uma excelente fonte para encontrar datasets em diversas áreas como saúde, finanças e marketing.

### 2. 📊 Análise Estatística Descritiva
Realize uma [análise exploratória dos dados (EDA)](https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15) para entender as características do dataset. 
Tarefas:
- Calcular medidas descritivas (média, mediana, desvio padrão, etc.).
- Visualizar distribuições com histogramas, boxplots, etc.
- Identificar outliers.
- Analisar correlações (matriz de correlação, heatmaps).

### 3. 🛠️ Pré-processamento de Dados
Prepare os dados antes de aplicar técnicas de AM.
Tarefas:
- Tratar valores ausentes (imputação ou remoção).
- Normalizar/padronizar os dados, se necessário.
- Codificar variáveis categóricas (one-hot, label encoding).
- Dividir o dataset em conjuntos de treino e teste.

### 4. 🔄 Treinamento e Teste com Cross-Validation
Aplique [cross-validation com k-folds](https://scikit-learn.org/stable/modules/cross_validation.html) para garantir que o modelo seja robusto e sem vieses.
Tarefas:
- Escolher o número de folds (geralmente 5 ou 10).
- Treinar o modelo com cada técnica de AM.

### 5. 🧠 Implementação de Técnicas de AM
Implemente duas técnicas de AM diferentes das usadas no Estudo X.
Tarefas:
- Utilize bibliotecas como [Scikit-learn](https://scikit-learn.org/stable/), [R](https://www.r-project.org/), ou [KNIME](https://www.knime.com/).
- Testar e validar os modelos.

### 6. ⚙️ Parametrização com Grid Search
Use [grid search](https://scikit-learn.org/stable/modules/grid_search.html) para otimizar os hiperparâmetros e encontrar a melhor versão dos modelos.
Tarefas:
- Definir o espaço de busca para cada hiperparâmetro.
- Executar o grid search para otimizar a performance.

### 7. 📈 Avaliação dos Modelos
Compare os resultados das duas técnicas de AM com os do Estudo X.
Tarefas:
- Calcular métricas de desempenho (acurácia, precisão, recall, F1-score, AUC-ROC).
- Criar gráficos comparativos entre os modelos desenvolvidos e o Estudo X.

🔗 **Referências úteis**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic), [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html).
