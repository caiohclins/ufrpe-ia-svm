# Classificação com Máquinas de Vetores de Suporte (SVM) no Conjunto de Dados Iris

Este projeto demonstra a aplicação de Máquinas de Vetores de Suporte (SVM) para resolver um problema de classificação usando o conjunto de dados iris. O SVM é uma técnica poderosa de aprendizado de máquina utilizada para classificação e regressão, sendo especialmente eficaz em conjuntos de dados de alta dimensionalidade.

## Objetivo

O objetivo deste notebook é construir, treinar e avaliar um modelo de classificação utilizando SVM no conjunto de dados iris, que contém informações sobre três espécies de íris. Este projeto inclui:

1. Carregamento e exploração do conjunto de dados iris.
2. Divisão do conjunto de dados em conjuntos de treino e teste.
3. Normalização dos dados.
4. Treinamento de um modelo SVM.
5. Avaliação do modelo utilizando métricas de desempenho.
6. Visualização das margens de decisão.

## Requisitos

Este projeto requer as seguintes bibliotecas Python:

- `pandas`: Manipulação de dados em estruturas de DataFrame.
- `numpy`: Operações numéricas.
- `scikit-learn`: Ferramentas para aprendizado de máquina, incluindo o SVM.
- `matplotlib`: Visualização de dados.
- `seaborn`: Visualização de dados e análise exploratória.

Você pode instalar essas dependências usando o seguinte comando:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Descrição do Conjunto de Dados

O conjunto de dados iris é um clássico em aprendizado de máquina e contém 150 amostras de flores de íris, cada uma com quatro características: comprimento e largura das sépalas, e comprimento e largura das pétalas. As amostras são divididas em três espécies: `setosa`, `versicolor` e `virginica`.

## Passos do Projeto

1. **Carregar o Conjunto de Dados Iris**: O conjunto de dados é carregado a partir da biblioteca `sklearn.datasets`, e suas características são armazenadas em um DataFrame do `pandas`.

2. **Divisão dos Dados**: Os dados são divididos em conjuntos de treino e teste, com 80% para treino e 20% para teste.

3. **Normalização dos Dados**: Os dados são normalizados para garantir que cada característica tenha média zero e variância unitária, o que melhora o desempenho do algoritmo SVM.

4. **Treinamento do Modelo SVM**: Um modelo SVM é treinado utilizando um kernel linear.

5. **Avaliação do Modelo**: O modelo é avaliado utilizando uma matriz de confusão e um relatório de classificação, fornecendo informações sobre a precisão, recall e F1-score.

6. **Visualização das Margens de Decisão**: As margens de decisão do modelo são visualizadas utilizando as duas primeiras características do conjunto de dados.
