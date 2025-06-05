# Detecção de Fraude em Transações de Cartão de Crédito

Este repositório contém um Jupyter Notebook chamado **Deteccao_Fraude_Revisado_Notebook.ipynb**, que implementa um pipeline completo de detecção de fraude em transações de cartão de crédito usando Deep Learning (TensorFlow). 

## 📋 Índice

1. [Descrição do Projeto](#descrição-do-projeto)  
2. [Conteúdo do Repositório](#conteúdo-do-repositório)  
3. [Pré-requisitos](#pré-requisitos)  
4. [Instalação e Configuração](#instalação-e-configuração)  
5. [Como Executar](#como-executar)  
6. [Estrutura do Notebook](#estrutura-do-notebook)  
7. [Referências](#referências)  

---

## Descrição do Projeto

O intuito deste projeto é construir um modelo capaz de identificar transações fraudulentas em um dataset de cartão de crédito. O notebook realiza:

- Exploração e análise exploratória dos dados (EDA).  
- Pré-processamento (normalização, tratamento do desbalanceamento).  
- Construção e treinamento de uma rede neural usando TensorFlow/Keras.  
- Avaliação da performance do modelo (métricas como acurácia, AUC, etc.).  
- Função para predição de novas transações.  

---

## Conteúdo do Repositório

- **Deteccao_Fraude_Revisado_Notebook.ipynb**  
  Jupyter Notebook completo com todo o pipeline de detecção de fraude.  

- **requirements.txt** *(opcional)*  
  Lista de dependências Python necessárias para rodar o notebook.  

- **README.md**  
  Este arquivo, contendo instruções de uso e referências.  

---

## Pré-requisitos

Antes de executar o notebook, você precisa ter instalado:

1. **Python 3.7 (ou superior)**  
2. **Jupyter Notebook** (ou JupyterLab)  
3. **Git** (caso queira clonar o repositório localmente)  

E, dentro do ambiente Python, as seguintes bibliotecas:
- pandas  
- numpy  
- matplotlib  
- scikit-learn  
- imbalanced-learn  
- tensorflow (versão 2.x)  
- seaborn *(opcional, se for usado no notebook)*  

---

## Instalação e Configuração

1. **Clonar este repositório (opcional):**
   ```bash
   git clone https://github.com/USERNAME/deteccao-fraude-notebook.git
   cd deteccao-fraude-notebook

