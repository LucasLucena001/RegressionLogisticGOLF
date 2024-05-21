# Regressão Logística: Predição de Jogo de Golfe

Este repositório contém um projeto de machine learning que utiliza a regressão logística para prever se as condições meteorológicas são adequadas para jogar golfe. Baseando-se em variáveis como clima, temperatura, umidade e vento, o modelo faz suas predições e oferece uma visão detalhada do processo de decisão.

## Estrutura do Projeto

O projeto inclui o seguinte arquivo principal:

- `regressionlogisticgolf.py`: Este script Python contém todo o código necessário para preparar os dados, treinar o modelo de regressão logística e avaliar suas predições.

Além disso, o dataset utilizado (não incluído neste repositório por questões de privacidade e tamanho) é um arquivo Excel chamado `golf_df.xlsx`, que deve estar no diretório `/content` quando o script é executado.

## Funcionalidades

Este projeto implementa as seguintes funcionalidades:

1. **Preparação de Dados**: Utiliza `LabelEncoder` para transformar variáveis categóricas em numéricas, permitindo que o modelo de regressão logística processe os dados.
   
2. **Modelagem e Treinamento**: Aplica o modelo de regressão logística aos dados transformados para entender as relações entre as condições meteorológicas e a decisão de jogar golfe.

3. **Predição e Avaliação**: Realiza predições sobre o dataset e avalia o modelo usando a matriz de confusão e o relatório de classificação para fornecer uma visão detalhada de sua precisão, recall e f1-score.

## Como Usar

Para executar este projeto, siga os passos abaixo:

1. **Prepare seu Ambiente**: Certifique-se de ter Python instalado, junto com as bibliotecas Pandas, NumPy e scikit-learn. Você pode instalar as dependências necessárias com:
   ```bash
   pip install pandas numpy scikit-learn
