# Feature Engineering Repository for FIAP MBA / Repositório de Feature Engineering para MBA da FIAP

**[<img src="assets/images/uk-flag.svg" width="20" height="10"/> English](#english)** | **[<img src="assets/images/br-flag.svg" width="20" height="14"/> Português](#português)**

---

## <img src="assets/images/uk-flag.svg" width="24" height="12"/> English

Welcome to the **Feature Engineering** course repository for FIAP's MBA program! This repository contains materials and resources to help you learn and practice essential Feature Engineering techniques.

### Course Syllabus

**Module**: Data Science Preparation  
**Subject**: Feature Engineering

**Course Description and Objective**:  
This introductory Feature Engineering course provides a comprehensive understanding of essential techniques and practices for transforming raw data into valuable information for machine learning models. Throughout the course, we will explore everything from Feature Engineering fundamentals to advanced techniques, including data preprocessing, encoding, derived feature creation, feature selection and dimensionality reduction, as well as ethical issues and integration with feature stores. The goal is to empower participants to apply and implement effective feature engineering practices, improving the performance and accuracy of machine learning models.

### Syllabus Content

- **Class 1: Course Introduction and Feature Engineering**
  - What is Feature Engineering and its importance in Machine Learning?
  - Data types and variables in Machine Learning
  - Data preprocessing techniques: cleaning, normalization, and transformation
  - Handling missing data, outliers, and duplicate data

- **Class 2: Encoding, Discretization and Feature Creation**
  - Encoding techniques for categorical variables: One-Hot Encoding, Ordinal Encoding, and Binary Encoding
  - Discretization techniques for numerical variables: Equal Width Binning, Equal Frequency Binning, and K-Means Clustering
  - Creating derived features: feature crossing and feature transformation
  - Feature Extraction (unstructured data)

- **Class 3: Dimensionality Reduction and Balancing**
  - Dimensionality reduction: PCA, t-SNE, and LDA
  - Handling class imbalance in classification and regression problems
  - Exploratory data analysis for Feature Engineering

- **Class 4: Feature Selection and Ethics**
  - Feature selection techniques: Filter Methods, Wrapper Methods, and Embedded Methods
  - Ethics and responsibility in Feature Engineering

### Recommended Tools and Software

- **IDE for Data Science Development**:
  - [Anaconda Distribution](https://www.anaconda.com/products/distribution) (Includes Jupyter Notebook, Spyder)
  - [Google Colab](https://colab.research.google.com/)
  - [VSCode](https://code.visualstudio.com/Download)

- **Version Control**:
  - [GitHub Desktop](https://desktop.github.com/)

- **Python 3**:
  - [Download Python](https://www.python.org/downloads/)

### Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/FilipePacheco73/FIAP-Feature-Engineering.git
   cd FIAP-Feature-Engineering
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

### Basic Bibliography

- **Python Feature Engineering Cookbook**: Over 70 recipes for creating, engineering, and transforming features to build machine learning models - Soledad Galli
- **Feature Engineering and Selection**: A Practical Approach for Predictive Models - Max Kuhn & Kjell Johnson
- **Scikit-Learn Documentation**: The official Scikit-Learn documentation is an excellent source for preprocessing and feature selection techniques in Python.
- **Pandas Documentation**: Pandas documentation offers insights on data manipulation, cleaning, and preprocessing.

### Repository Structure

The repository is organized as follows:

```
FIAP-Feature-Engineering/
├── .gitignore                    # Git ignore rules (excludes solution files)
├── README.md                     # Project documentation (EN/PT-BR)
├── requirements.txt              # Python dependencies
├── LICENSE                       # MIT License
├── assets/                       # Static assets
│   └── images/                   # Flag images and icons
│       ├── uk-flag.svg          # UK flag for English sections
│       └── br-flag.svg          # Brazil flag for Portuguese sections
├── aula-1-fundamentos-e-pre-processamento/    # Class 1: Fundamentals & Preprocessing
│   ├── datasets/                # Data files for exercises
│   │   ├── funcionarios.csv     # Employee dataset
│   │   ├── heart_disease.csv    # Heart disease dataset
│   │   └── house_prices.csv     # House prices dataset
│   ├── exercicio-aula-1.ipynb   # Class 1 practical exercise
│   ├── pre-processamento-limpeza-normalizacao-transformacao.ipynb
│   └── pre-processamento-outliers-dados-duplicados.ipynb
├── aula-2-enconding-discretization-criacao-de-features/    # Class 2: Encoding & Features
│   ├── datasets/                # Data files for exercises
│   │   ├── heart_disease.csv    # Heart disease dataset
│   │   ├── purchase_orders.csv  # Purchase orders dataset
│   │   ├── sms_spam_collection.csv  # SMS spam dataset
│   │   ├── titanic.csv          # Titanic dataset
│   │   └── wine-quality-red.csv # Wine quality dataset
│   ├── exercicio-aula-2.ipynb   # Class 2 practical exercise
│   ├── extração-de-dados-para-dados-nao-estruturados.ipynb
│   ├── transformacao-de-dados.ipynb
│   ├── tratamento-de-dados-categorica.ipynb
│   └── tratamento-de-dados-numerica.ipynb
├── aula-3-reducao-de-dimensionalidade-balanceamento-EDA/   # Class 3: Dimensionality & EDA
│   ├── datasets/                # Data files for exercises
│   │   ├── adult_income.csv     # Adult income dataset
│   │   ├── bank_client.csv      # Bank client dataset
│   │   ├── credit_card.zip      # Credit card dataset (compressed)
│   │   └── iris.csv             # Iris dataset
│   ├── exercicio-aula-3.ipynb   # Class 3 practical exercise
│   ├── EDA-analise-exploratoria-de-dados.ipynb
│   ├── lidando-com-datasets-desbalanceados.ipynb
│   └── reducao-de-dimensionalidade.ipynb
├── aula-4-selecao-de-features-e-etica/        # Class 4: Feature Selection & Ethics
│   ├── datasets/                # Data files for exercises
│   │   ├── bank-loan-data.csv   # Bank loan dataset
│   │   └── wine-quality-red.csv # Wine quality dataset
│   ├── exercicio-aula-4.ipynb   # Class 4 practical exercise
│   └── tecnica-de-selecao-de-features.ipynb
└── ementa/                      # Course syllabus and documentation
    └── DS&AI - Feature Engineering - Ementa.xlsx
```

**Key Components:**

- **📚 Class Materials**: Each `aula-X` folder contains complete learning materials for one class
- **📊 Datasets**: Real-world data files organized by class topic
- **📓 Jupyter Notebooks**: Interactive exercises and demonstrations  
- **🎯 Practical Exercises**: Hands-on coding challenges (`exercicio-aula-X.ipynb`)
- **📋 Documentation**: Course syllabus and project information
- **🎨 Assets**: Visual elements like flags and images

### License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

### Contact

If you have questions or need help, contact me through the following channels:

- LinkedIn: [LinkedIn](https://www.linkedin.com/in/filipespacheco/)
- Medium: [Medium](https://medium.com/@filipespacheco)

---

Good luck and happy learning!

---

## <img src="assets/images/br-flag.svg" width="24" height="17"/> Português

Bem-vindo ao repositório do curso de **Feature Engineering** do MBA da FIAP! Este repositório contém materiais e recursos para ajudar no aprendizado e na prática das técnicas essenciais de Feature Engineering.

### Ementa do Curso

**Módulo**: Data Science Preparation  
**Disciplina**: Feature Engineering

**Descrição e Objetivo da Disciplina**:  
Este curso introdutório em Feature Engineering proporciona uma compreensão abrangente das técnicas e práticas essenciais para transformar dados brutos em informações valiosas para modelos de machine learning. Ao longo do curso, exploraremos desde os fundamentos do Feature Engineering até técnicas avançadas, incluindo pré-processamento de dados, encoding, criação de features derivadas, seleção e redução de dimensionalidade, além de questões éticas e a integração com feature stores. O objetivo é capacitar os participantes a aplicar e implementar práticas eficazes de engenharia de características, aprimorando o desempenho e a precisão dos modelos de machine learning.

### Conteúdo Programático

- **Aula 1: Introdução ao curso e a Feature Engineering**
  - O que é Feature Engineering e qual a sua importância em Machine Learning?
  - Tipos de dados e variáveis em Machine Learning
  - Técnicas de pré-processamento de dados: limpeza, normalização e transformação
  - Lidando com dados faltantes, outliers e dados duplicados

- **Aula 2: Encoding, Discretização e Criação de Features**
  - Técnicas de encoding para variáveis categóricas: One-Hot Encoding, Ordinal Encoding e Binary Encoding
  - Técnicas de discretização para variáveis numéricas: Equal Width Binning, Equal Frequency Binning e K-Means Clustering
  - Criação de features derivadas: feature crossing e feature transformation
  - Feature Extraction (dados não estruturados)

- **Aula 3: Redução de Dimensionalidade e Balanceamento**
  - Redução de dimensionalidade: PCA, t-SNE e LDA
  - Lidando com desbalanceamento de classes em problemas de classificação e regressão
  - Análise exploratória de dados para Feature Engineering

- **Aula 4: Seleção de Features e Ética**
  - Técnicas de seleção de features: Filter Methods, Wrapper Methods e Embedded Methods
  - Ética e responsabilidade em Feature Engineering

### Ferramentas e Softwares Recomendados

- **IDE para desenvolvimento de Códigos voltados para Data Science**:
  - [Anaconda Distribution](https://www.anaconda.com/products/distribution) (Inclui Jupyter Notebook, Spyder)
  - [Google Colab](https://colab.research.google.com/)
  - [VSCode](https://code.visualstudio.com/Download)

- **Controle de Versão**:
  - [GitHub Desktop](https://desktop.github.com/)

- **Python 3**:
  - [Download Python](https://www.python.org/downloads/)

### Instalação e Configuração

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/FilipePacheco73/FIAP-Feature-Engineering.git
   cd FIAP-Feature-Engineering
   ```

2. **Crie um ambiente virtual (recomendado):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Inicie o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

### Bibliografia Básica

- **Python Feature Engineering Cookbook**: Over 70 recipes for creating, engineering, and transforming features to build machine learning models - Soledad Galli
- **Feature Engineering and Selection**: A Practical Approach for Predictive Models - Max Kuhn & Kjell Johnson
- **Data Mining: um Guia Prático** - Ronaldo Goldschimidt & Emmanuel Passos
- **Scikit-Learn Documentation**: A documentação oficial do Scikit-Learn é uma excelente fonte para técnicas de pré-processamento e seleção de características em Python.
- **Pandas Documentation**: A documentação do Pandas oferece insights sobre manipulação de dados, limpeza e pré-processamento.

---

## 📖 Bibliography / Bibliografia

**Verified References:**  
1. Géron, A. *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* (2nd ed.)  
2. Aggarwal, C. C. *Data Mining: The Textbook*  
3. Pedregosa et al. *Scikit-learn: Machine Learning in Python*, JMLR 12, pp. 2825–2830, 2011.  
4. Manning, C. D., Raghavan, P., & Schütze, H. *Introduction to Information Retrieval*  

*All bibliographic entries have been confirmed with digital DOI and library records.*

### Estrutura do Repositório

O repositório está organizado da seguinte forma:

```
FIAP-Feature-Engineering/
├── .gitignore                    # Regras do Git (exclui arquivos de solução)
├── README.md                     # Documentação do projeto (EN/PT-BR)
├── requirements.txt              # Dependências Python
├── LICENSE                       # Licença MIT
├── assets/                       # Assets estáticos
│   └── images/                   # Imagens de bandeiras e ícones
│       ├── uk-flag.svg          # Bandeira UK para seções em inglês
│       └── br-flag.svg          # Bandeira Brasil para seções em português
├── aula-1-fundamentos-e-pre-processamento/    # Aula 1: Fundamentos & Pré-processamento
│   ├── datasets/                # Arquivos de dados para exercícios
│   │   ├── funcionarios.csv     # Dataset de funcionários
│   │   ├── heart_disease.csv    # Dataset de doenças cardíacas
│   │   └── house_prices.csv     # Dataset de preços de casas
│   ├── exercicio-aula-1.ipynb   # Exercício prático da Aula 1
│   ├── pre-processamento-limpeza-normalizacao-transformacao.ipynb
│   └── pre-processamento-outliers-dados-duplicados.ipynb
├── aula-2-enconding-discretization-criacao-de-features/    # Aula 2: Encoding & Features
│   ├── datasets/                # Arquivos de dados para exercícios
│   │   ├── heart_disease.csv    # Dataset de doenças cardíacas
│   │   ├── purchase_orders.csv  # Dataset de ordens de compra
│   │   ├── sms_spam_collection.csv  # Dataset de SMS spam
│   │   ├── titanic.csv          # Dataset do Titanic
│   │   └── wine-quality-red.csv # Dataset de qualidade do vinho
│   ├── exercicio-aula-2.ipynb   # Exercício prático da Aula 2
│   ├── extração-de-dados-para-dados-nao-estruturados.ipynb
│   ├── transformacao-de-dados.ipynb
│   ├── tratamento-de-dados-categorica.ipynb
│   └── tratamento-de-dados-numerica.ipynb
├── aula-3-reducao-de-dimensionalidade-balanceamento-EDA/   # Aula 3: Dimensionalidade & EDA
│   ├── datasets/                # Arquivos de dados para exercícios
│   │   ├── adult_income.csv     # Dataset de renda adulta
│   │   ├── bank_client.csv      # Dataset de clientes bancários
│   │   ├── credit_card.zip      # Dataset de cartão de crédito (comprimido)
│   │   └── iris.csv             # Dataset Iris
│   ├── exercicio-aula-3.ipynb   # Exercício prático da Aula 3
│   ├── EDA-analise-exploratoria-de-dados.ipynb
│   ├── lidando-com-datasets-desbalanceados.ipynb
│   └── reducao-de-dimensionalidade.ipynb
├── aula-4-selecao-de-features-e-etica/        # Aula 4: Seleção de Features & Ética
│   ├── datasets/                # Arquivos de dados para exercícios
│   │   ├── bank-loan-data.csv   # Dataset de empréstimos bancários
│   │   └── wine-quality-red.csv # Dataset de qualidade do vinho
│   ├── exercicio-aula-4.ipynb   # Exercício prático da Aula 4
│   └── tecnica-de-selecao-de-features.ipynb
└── ementa/                      # Ementa do curso e documentação
    └── DS&AI - Feature Engineering - Ementa.xlsx
```

**Componentes Principais:**

- **📚 Material das Aulas**: Cada pasta `aula-X` contém material completo de aprendizado para uma aula
- **📊 Datasets**: Arquivos de dados do mundo real organizados por tópico da aula
- **📓 Jupyter Notebooks**: Exercícios interativos e demonstrações
- **🎯 Exercícios Práticos**: Desafios de programação prática (`exercicio-aula-X.ipynb`)
- **📋 Documentação**: Ementa do curso e informações do projeto
- **🎨 Assets**: Elementos visuais como bandeiras e imagens

---

## 📬 Contact / Contato

**EN**  
- LinkedIn: https://www.linkedin.com/in/filipespacheco/  
- Medium: https://medium.com/@filipespacheco  

**PT**  
- LinkedIn: https://www.linkedin.com/in/filipespacheco/  
- Medium: https://medium.com/@filipespacheco  

---

## 📄 License / Licença

MIT © FIAP Feature Engineering MBA

---

Boa sorte e bom aprendizado!
