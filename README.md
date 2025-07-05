# Projeto de Mineração de Dados - Análise de Doenças Cardíacas com WEKA

Este projeto foi desenvolvido como parte da avaliação da disciplina de **Tópicos Especiais em Computação I**.  
O objetivo foi utilizar o software **WEKA** para analisar um conjunto de dados sobre doenças cardíacas, aplicando a técnica de **regressão** para prever o grau da doença com base em atributos clínicos e físicos dos pacientes.

---

## Dataset

- **Nome:** Heart Disease Dataset  
- **Origem:** [Kaggle - Heart Disease Data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)  
- **Descrição:** O dataset contém **920 registros** com **16 atributos**, incluindo informações como idade, sexo, pressão sanguínea, colesterol, frequência cardíaca, entre outros.  
  O atributo alvo (`num`) representa a gravidade da doença cardíaca.

---

## Ferramentas e Técnicas

- **Software:** WEKA (Waikato Environment for Knowledge Analysis)  
- **Técnica de Mineração:** Regressão  
- **Algoritmo:** Árvore de Regressão (REPTree)

---

## Como Reproduzir a Análise

1. Baixe o arquivo `heart_disease_uci_final.arff` do link do Kaggle ou utilize o arquivo fornecido neste repositório.
2. Baixe e instale o software **[WEKA](https://www.cs.waikato.ac.nz/ml/weka/downloading.html)**.
3. Abra o **WEKA Explorer**.
4. Clique em "Open file..." e selecione o arquivo `.arff`.
5. Vá até a aba "Classify".
6. Clique em "Choose" → "trees" → "REPTree".
7. Em "Test options", mantenha a opção padrão "Cross-validation" com 10 folds.
8. Certifique-se de que o atributo alvo está definido como "(Num) quality".
9. Clique em "Start" para iniciar a análise de regressão.
10. Os resultados serão exibidos na área "Classifier output".
