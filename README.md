# 📊 Análise de Personalidade com Regressão Logística

## 📌 Sobre o Projeto

Este projeto aplica **Regressão Logística** para prever se um indivíduo é **Introvertido** ou **Extrovertido** com base na frequência com que sai de casa.

O objetivo foi analisar a relação entre comportamento social observável e traços de personalidade utilizando modelagem estatística.

---

## 🗂 Base de Dados

- Dataset: Extrovert vs Introvert Behavior Data  
- Fonte: Kaggle  
- 2900 registros  
- 8 variáveis  
- Variável utilizada: `Going_outside`  

---

## 🛠 Tecnologias Utilizadas

- Python  
- Pandas  
- Scikit-learn  
- Statsmodels  
- Seaborn  
- Matplotlib  

---

## 📈 Resultados

- **Acurácia:** 93%  
- Precision e Recall equilibrados  
- Modelo estatisticamente significativo  

O modelo classificou corretamente:
- 249 Introvertidos  
- 276 Extrovertidos  

Apresentando poucos erros de classificação e boa capacidade de generalização.

---

## 📊 Principais Insights

- Quanto maior a frequência de sair de casa, maior a probabilidade de extroversão.  
- O modelo apresentou excelente desempenho mesmo utilizando apenas uma variável preditora.  
- A curva logística apresentou o comportamento sigmoidal esperado.  

---

## 📂 Estrutura do Projeto

analise-personalidade-regressao-logistica/
├── README.md
├── data/
│   └── personality_dataset.csv
├── notebooks/
│   └── regressao_logistica.ipynb

## 🚀 Como Executar

Instale as dependências:

pip install pandas scikit-learn statsmodels seaborn matplotlib

Abra o notebook na pasta `notebooks`.
