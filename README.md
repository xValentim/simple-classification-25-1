# Titanic Survival Prediction - Binary Classification with Logistic Regression

Este repositório contém um projeto de Machine Learning que aplica um modelo de **Regressão Logística** para prever a sobrevivência de passageiros do Titanic com base em suas características. O projeto utiliza o Titanic Dataset, um conjunto de dados famoso para problemas de classificação binária.

## Objetivo do Projeto

O objetivo deste projeto é desenvolver um modelo preditivo que classifique se um passageiro sobreviveria ou não ao naufrágio do Titanic com base em atributos como idade, sexo, classe socioeconômica, número de familiares a bordo, entre outros. Esse problema de classificação binária é abordado usando a Regressão Logística como modelo principal.

## Estrutura do Projeto

1. **Aquisição e Compreensão dos Dados**:
   - Carregamento e análise inicial do Titanic Dataset.
   - Identificação de variáveis categóricas (ex.: `Sex`, `Embarked`) e numéricas (ex.: `Age`, `Fare`).
   - Definição da variável-alvo (`Survived`) e das features que serão utilizadas para previsão.

2. **Análise Exploratória de Dados (EDA)**:
   - Análise das distribuições das variáveis numéricas e categóricas.
   - Avaliação de relações entre as variáveis e a sobrevivência dos passageiros.

3. **Pré-processamento de Dados**:
   - Tratamento de valores ausentes.
   - Transformação de variáveis categóricas em variáveis dummy.
   - Escalonamento das variáveis numéricas para garantir melhor desempenho e estabilidade do modelo de Regressão Logística.

4. **Treinamento e Avaliação do Modelo**:
   - Divisão do conjunto de dados em treino e validação.
   - Treinamento do modelo de Regressão Logística.
   - Avaliação do modelo com métricas como acurácia, matriz de confusão, precisão e recall.

5. **Análise de Desempenho e Ajustes**:
   - Ajustes no modelo com base na análise de erros.
   - Considerações sobre o impacto de diferentes variáveis na sobrevivência.

## Estrutura dos Arquivos

- `simple_classification.ipynb`: Jupyter Notebook principal contendo todo o processo de análise, pré-processamento, treinamento e avaliação do modelo de Regressão Logística.
- `README.md`: Descrição do projeto, objetivos e estrutura.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Pandas**: Manipulação e análise de dados.
- **NumPy**: Operações matemáticas e tratamento de arrays.
- **Scikit-Learn**: Treinamento e avaliação do modelo de Regressão Logística.
- **Matplotlib e Seaborn**: Visualização de dados para EDA.

## Como Executar o Projeto

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu_usuario/titanic_survival_classification.git
   ```

2. Instale os pacotes necessários:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute o Jupyter Notebook:

   ```bash
   jupyter notebook simple_classification.ipynb
   ```

4. Siga as etapas do notebook para carregar os dados, pré-processar, treinar e avaliar o modelo.

## Resultados

O modelo de Regressão Logística treinado neste projeto apresentou uma acurácia de aproximadamente 80.36% no treinamento.