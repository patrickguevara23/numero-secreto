# Classificação de e-mail como SPAM

Este projeto utiliza técnicas de Processamento de Linguagem Natural (NLP) e algoritmos de Machine Learning para classificar e-mails como SPAM ou NÃO-SPAM. Os modelos foram treinados e avaliados utilizando um conjunto de dados contendo e-mails classificados. O objetivo é criar um sistema eficiente que possa ajudar na filtragem automática de mensagens indesejadas.

---

## 🔍 **Descrição do Projeto**

A classificação é baseada em técnicas de NLP para análise textual, como:
- Vetorização do texto usando CountVectorizer.
- Limpeza e pré-processamento dos dados, como:
    - remoção de stopwords e normalização dos textos.
    - remoção de acentuação e pontuação.
    - converter palavras para o minúsculo e remoção de sufixos e prefixos
    - TF-IDF e n-Grams

### **Valores de Saída (Target)**
- `0`: Não SPAM 
- `1`: SPAM

---

## ⚙️ **Modelo de Machine Learning**

- Regressão Logística

---

## 🛠️ **Ferramentas e Tecnologias**

- **Linguagem**: Python  
- **Bibliotecas**:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Statsmodel  
  - SciPy
  - Nltk
  - String
  - Matplotlib
  - WordCloud

---

## 🧪 **Estrutura do Projeto**


├── data/                       # Conjunto de dados utilizado no projeto

├── Projeto_Diabetes.ipynb      # Notebooks com análise exploratória e modelos

└── README.md                   # Documentação do projeto
