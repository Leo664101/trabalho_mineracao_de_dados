# Projeto de Mineração de Dados - Análise de Qualidade de Vinho com WEKA

Este projeto foi desenvolvido como parte da avaliação da disciplina de **Tópicos Especiais em Computação I**. O objetivo foi utilizar o software **WEKA** para analisar um conjunto de dados sobre vinhos, aplicando a técnica de **regressão** para estimar a qualidade de um vinho com base em suas características físico-químicas.

## Dataset

- **Nome:** Wine Quality (Qualidade do Vinho - Tinto)  
- **Origem:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
- **Descrição:** O dataset contém **1.599** amostras de vinho tinto português "Vinho Verde", com **11 atributos físico-químicos** e uma **nota de qualidade** (atributo alvo).

## Ferramentas e Técnicas

- **Software:** WEKA (Waikato Environment for Knowledge Analysis)  
- **Técnica de Mineração:** Regressão  
- **Algoritmo:** Árvore de Regressão (REPTree)

## Como Reproduzir a Análise

1. Baixe o arquivo `winequality-red.csv` do link acima.  
1. Baixe e instale o software [WEKA](https://www.cs.waikato.ac.nz/ml/weka/).  
2. Abra o **WEKA Explorer**.  
3. Clique em **"Open file..."** e selecione o arquivo `vinho.csv`.  
4. Vá até a aba **"Classify"**.  
5. Clique em **"Choose"** → **"trees"** → **"REPTree"**.  
6. Em **"Test options"**, mantenha a opção padrão **"Cross-validation"** com **10 folds**.  
7. Certifique-se de que o atributo alvo está definido como **"(Num) quality"**.  
8. Clique em **"Start"** para iniciar a análise de regressão.  
9. Os resultados serão exibidos na área **"Classifier output"**.
