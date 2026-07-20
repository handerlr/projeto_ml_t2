# Projeto: Análise de Risco de Crédito

## Objetivo
Este projeto tem como objetivo desenvolver um Pipeline Preditivo para avaliar o risco de inadimplência de clientes, utilizando técnicas de Ciência de Dados para apoiar a tomada de decisão financeira.

## Metodologia
1. **Limpeza e Tratamento:** Tratamento de valores nulos e análise de consistência.
2. **Engenharia de Variáveis:** Criação e seleção de features relevantes.
3. **Modelagem:** Implementação de algoritmos de Machine Learning (KNN e Árvores de Decisão).
4. **Otimização:** Ajuste de hiperparâmetros para evitar overfitting.

## Tecnologias Utilizadas
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imblearn

# Análise de Risco de Crédito: Predição de Inadimplência

Este repositório contém o projeto de análise de dados e modelagem preditiva desenvolvido para o curso de Introdução à Inteligência Artificial. O objetivo é identificar perfis de risco de crédito, minimizando prejuízos financeiros.

## 1. Descrição do Problema de Negócio
Instituições financeiras precisam equilibrar a expansão da carteira de clientes com o controle de inadimplência (default). Erros de predição impactam diretamente o resultado:
*   **Falso Negativo (Calote):** O modelo falha ao identificar um mau pagador. Impacto crítico, gerando perda de capital.
*   **Falso Positivo (Oportunidade Perdida):** O modelo recusa crédito a um bom pagador. Impacto moderado, gerando perda de receita por juros.

O objetivo deste projeto é minimizar o risco de crédito através de um modelo estatístico robusto.

## 2. Dicionário de Dados

| Coluna | Descrição |
| :--- | :--- |
| `loan_amnt` | Valor total do empréstimo solicitado. |
| `person_income` | Renda anual declarada do cliente. |
| `comprometimento_renda` | Feature de engenharia: `(loan_amnt / person_income) * 100`. |
| `loan_status` | Variável alvo (0: Bom pagador, 1: Mau pagador). |

## 3. Instalação e Execução

### Pré-requisitos
*   Python 3.x
*   Ambiente virtual recomendado (venv ou conda)

### Passo a passo
1. **Clone este repositório:**
   ```bash
   git clone https://github.com/handerlr/projeto_ml_t2.git

### Instalação e Execução

1. **Acesse a pasta do projeto:**
    ```bash
    cd projeto_ml_t2

1. **Instale as dependências:**
    ```bash

    pip install -r requirements.txt
---
*Desenvolvido por: Anderson*

# Análise de Risco de Crédito: Predição de Inadimplência

Este repositório contém o projeto de análise de dados e modelagem preditiva desenvolvido para o curso de Introdução à Inteligência Artificial. O objetivo é identificar perfis de risco de crédito, minimizando prejuízos financeiros.

## 1. Descrição do Problema de Negócio
Instituições financeiras precisam equilibrar a expansão da carteira de clientes com o controle de inadimplência (default). Erros de predição impactam diretamente o resultado:
*   **Falso Negativo (Calote):** O modelo falha ao identificar um mau pagador. Impacto crítico, gerando perda de capital.
*   **Falso Positivo (Oportunidade Perdida):** O modelo recusa crédito a um bom pagador. Impacto moderado, gerando perda de receita por juros.

O objetivo deste projeto é minimizar o risco de crédito através de um modelo estatístico robusto.

## 2. Dicionário de Dados

| Coluna | Descrição |
| :--- | :--- |
| `loan_amnt` | Valor total do empréstimo solicitado. |
| `person_income` | Renda anual declarada do cliente. |
| `comprometimento_renda` | Feature de engenharia: `(loan_amnt / person_income) * 100`. |
| `loan_status` | Variável alvo (0: Bom pagador, 1: Mau pagador). |

## 3. Instalação e Execução

### Pré-requisitos
*   Python 3.x
*   Ambiente virtual recomendado (venv ou conda)

### Passo a passo
1. **Clone este repositório:**
   git clone
   [https://github.com/handerlr/projeto_ml_t2.git](https://github.com/handerlr/projeto_ml_t2.git)

3. **Acesse a pasta do projeto:**
    ```bash
    cd nome-do-repositorio
4. **Instale as dependências:**
5. ```bash
    pip install -r requirements.txt

# Análise de Risco de Crédito: Predição de Inadimplência

Este repositório contém o projeto de análise de dados e modelagem preditiva desenvolvido para o curso de Introdução à Inteligência Artificial. O objetivo é identificar perfis de risco de crédito, minimizando prejuízos financeiros.

## 1. Descrição do Problema de Negócio
Instituições financeiras precisam equilibrar a expansão da carteira de clientes com o controle de inadimplência (default). Erros de predição impactam diretamente o resultado:
*   **Falso Negativo (Calote):** O modelo falha ao identificar um mau pagador. Impacto crítico, gerando perda de capital.
*   **Falso Positivo (Oportunidade Perdida):** O modelo recusa crédito a um bom pagador. Impacto moderado, gerando perda de receita por juros.

O objetivo deste projeto é minimizar o risco de crédito através de um modelo estatístico robusto.

## 2. Dicionário de Dados

| Coluna | Descrição |
| :--- | :--- |
| `loan_amnt` | Valor total do empréstimo solicitado. |
| `person_income` | Renda anual declarada do cliente. |
| `comprometimento_renda` | Feature de engenharia: `(loan_amnt / person_income) * 100`. |
| `loan_status` | Variável alvo (0: Bom pagador, 1: Mau pagador). |

## 3. Instalação e Execução

### Pré-requisitos
*   Python 3.x
*   Ambiente virtual recomendado (venv ou conda)

### Passo a passo
1. **Clone este repositório:**
   ```bash
   git clone https://github.com/handerlr/projeto_ml_t2.git
2. **Acesse a pasta do projeto:**
    ```bash
    cd nome-do-repositorio
3. **Instale as dependências:**
4. ```bash
    pip install -r requirements.txt