# San Francisco Crime Classification  

Este repositório contém a implementação do projeto de classificação de crimes em São Francisco, baseado no desafio disponível no [Kaggle](https://www.kaggle.com/competitions/sf-crime/overview). O objetivo é prever a categoria de crimes com base em dados históricos, aplicando técnicas de mineração de dados e aprendizado de máquina.  

## Descrição do Problema  
Entre 01/01/2003 e 13/05/2015, crimes foram registrados em todos os bairros de São Francisco. O conjunto de dados inclui informações como:  
- **Data e hora** do crime.  
- **Descrição detalhada** do crime (apenas no conjunto de treinamento).  
- **Dia da semana**.  
- **Distrito policial**.  
- **Resolução** (apenas no conjunto de treinamento).  
- **Endereço**, **longitude** e **latitude**.  
- **Categoria do crime**, que é a variável alvo para a previsão.  

Dado o tempo e o local, o objetivo é prever a categoria do crime ocorrido.  

## Motivação  
Este projeto foi desenvolvido na disciplina **BCC444 - Mineração de Dados** na Universidade Federal de Ouro Preto (UFOP). Ele tem como objetivo explorar o pré-processamento de dados, lidar com valores incompletos e realizar previsões com base nos dados transformados. A tarefa de prever crimes é uma aplicação prática dos conceitos estudados e demonstra a importância do tratamento e modelagem de dados.  

## Objetivo do Projeto  
O trabalho é composto pelas seguintes etapas:  
1. **Pré-processamento** dos dados para garantir consistência e qualidade.  
2. **Treinamento de um modelo de IA** para aprendizado e categorização de crimes.  
3. Avaliação do modelo para medir a **precisão** na categorização.  

## Tecnologias Utilizadas  
- Python  
- Bibliotecas de Ciência de Dados: Pandas, NumPy, Scikit-learn, etc.  
- Visualização: Matplotlib, Seaborn  
- Machine Learning: Modelos supervisionados para classificação  

## Como Executar  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/henrique-dpighini/sf-crime-classification.git
   cd sf-crime-classification

