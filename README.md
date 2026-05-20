# Classificação de Tumores de Mama com Inteligência Artificial

Projeto desenvolvido para a disciplina de Inteligência Artificial do curso de Engenharia da Computação do Instituto Federal da Paraíba (IFPB). O objetivo é aplicar técnicas de aprendizado de máquina para classificar tumores de mama como **benignos** ou **malignos** utilizando o Wisconsin Breast Cancer Dataset.

\---

## 📌 Objetivo

Este projeto tem como finalidade desenvolver um sistema de classificação supervisionada capaz de identificar tumores de mama a partir de características extraídas de exames médicos.

Durante o desenvolvimento, são abordadas etapas fundamentais de um pipeline de Machine Learning, incluindo:

* Análise Exploratória de Dados (EDA)
* Pré-processamento e preparação dos dados
* Treinamento de modelos de classificação
* Avaliação de desempenho
* Interpretação dos resultados

\---

## 🧠 Dataset

O projeto utiliza o dataset Wisconsin Breast Cancer Dataset.

O conjunto de dados contém características numéricas extraídas de imagens digitalizadas de células obtidas por biópsias de mama, como:

* raio médio
* textura
* perímetro
* área
* concavidade
* simetria

As classes do problema são:

* **Benigno**
* **Maligno**

O dataset pode ser carregado diretamente utilizando a biblioteca `scikit-learn`.

\---

## 🛠️ Tecnologias Utilizadas

* Python 3
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

\---

## 📂 Estrutura do Projeto

```bash
📁 projeto-ia-tumores
│
├── data/                 # Dataset
├── notebooks/            # Análises e experimentos
├── models/               # Modelos treinados
├── images/               # Gráficos e imagens
├── src/                  # Scripts auxiliares
├── requirements.txt
└── README.md
```

\---

## 📊 Etapas do Projeto

### 1\. Análise Exploratória dos Dados (EDA)

Nesta etapa são realizadas análises estatísticas e visuais do dataset:

* distribuição das classes
* estatísticas descritivas
* análise de correlação
* histogramas
* boxplots
* mapas de calor

\---

### 2\. Pré-processamento

Os dados passam por etapas de preparação, como:

* verificação de valores ausentes
* normalização/padronização
* separação em treino e teste

\---

### 3\. Treinamento dos Modelos

Os seguintes algoritmos podem ser utilizados:

* Regressão Logística
* Support Vector Machine (SVM)
* Árvore de Decisão
* Random Forest
* Redes Neurais Artificiais

\---

### 4\. Avaliação dos Modelos

As métricas utilizadas incluem:

* Acurácia
* Precisão
* Recall (Sensibilidade)
* F1-score
* Matriz de Confusão

\---

## ▶️ Como Executar

### Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### Acesse a pasta do projeto

```bash
cd seu-repositorio
```

### Instale as dependências

```bash
pip install -r requirements.txt
```

### Execute o notebook

```bash
jupyter notebook
```

\---

## 🎯 Resultados Esperados

Espera-se comparar diferentes modelos de aprendizado de máquina e identificar qual apresenta melhor desempenho para classificação de tumores.

Além disso, o projeto busca discutir:

* impacto de falsos positivos e falsos negativos
* limitações dos modelos
* aplicações de IA na área médica

\---

## ⚖️ Reflexão Ética

O uso de Inteligência Artificial em aplicações médicas envolve desafios importantes, como:

* riscos de diagnósticos incorretos
* confiabilidade dos sistemas automatizados
* responsabilidade no uso da IA em saúde

\---

## 👨‍💻 Autor(es)

Projeto desenvolvido para a disciplina de Inteligência Artificial — IFPB.

\---

## 📄 Licença

Este projeto possui fins acadêmicos e educacionais.

