# Breast Cancer Wisconsin (Diagnostic) - Análise e Classificação

Este repositório contém scripts e análises voltados para o estudo e a modelagem preditiva utilizando o clássico **Breast Cancer Wisconsin (Diagnostic) Dataset**. O objetivo principal deste projeto é aplicar técnicas de Machine Learning para realizar a classificação binária de tumores em **Malignos** ou **Benignos**, com base em características celulares extraídas de exames.

---

## 📁 Estrutura Sugerida do Projeto

- **breast-cancer-analysis/**
  - **data/**
    - `breast_cancer_wisconsin.data` (Arquivo de dados brutos)
  - **src/**
    - `main.py` (Script principal de pré-processamento e modelos)
  - **assets/** (Gráficos e imagens geradas)
  - `README.md` (Documentação do projeto)

---

## 📊 Sobre o Dataset

O conjunto de dados descreve características numéricas dos núcleos celulares presentes em imagens digitalizadas de punção aspirativa por agulha fina (FNA) de massas mamárias. 

* **Total de instâncias:** 569 amostras.
* **Atributos preditivos:** 30 variáveis numéricas (calculadas como a média, o erro padrão e o pior/maior valor para propriedades como raio, textura, perímetro, área, suavidade, compacidade, concavidade, pontos côncavos, simetria e dimensão fractal).
* **Variável Alvo (Target):** Classificação do diagnóstico (`Maligno` ou `Benigno`).

---

## ⚙️ Etapas do Pipeline

1. **Análise Exploratória de Dados (EDA):**
   * Limpeza e verificação de valores ausentes.
   * Estudo de correlação entre as variáveis preditivas para remoção de multicolinearidade, se necessário.
2. **Pré-processamento:**
   * Padronização e normalização das features numéricas (essencial para algoritmos baseados em distância).
   * Divisão dos dados em conjuntos de treino e teste.
3. **Modelagem Preditiva:**
   * Treinamento de algoritmos de classificação (como Regressão Logística, SVM, Random Forest, etc.).
4. **Avaliação de Desempenho:**
   * Análise baseada em Acurácia, Matriz de Confusão, *Precision*, *Recall* (essencial na área médica para evitar falsos negativos) e Curva ROC-AUC.

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* **Pandas & NumPy** (Manipulação e estruturação de dados)
* **Scikit-Learn** (Algoritmos de Machine Learning e métricas de avaliação)
* **Matplotlib & Seaborn** (Visualização gráfica de dados estatísticos)

---

## 🚀 Como Executar

1. Clone o repositório para o seu ambiente local:
   ```bash
   git clone [https://github.com/LeonardoCorreia08/seu-repositorio.git](https://github.com/LeonardoCorreia08/seu-repositorio.git)
