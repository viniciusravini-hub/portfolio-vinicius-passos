# 🏙️ Análise e simulação em Python

## 📝 Descrição do Projeto
Este repositório contém um conjunto de simuladores desenvolvidos em Python voltados para a análise de dados urbanos e segurança civil. O projeto está dividido em dois módulos principais que utilizam lógica de programação estruturada e tomada de decisão algorítmica para resolver problemas do cotidiano das metrópoles.

1. Análise de Microclima (Zona Leste - SP)
Um motor de processamento que avalia o conforto ambiental de diferentes bairros de São Paulo.
Cálculo de Nota de Conforto: Algoritmo que pondera temperatura, umidade e o Índice de Qualidade do Ar (IQA).
Classificação CETESB: Integração com as faixas oficiais da Companhia Ambiental do Estado de São Paulo para categorizar riscos à saúde.

2. Simulador de Evacuacão Predial
Um sistema baseado em agentes que modela a saída de emergência em uma instituição de ensino.
Gestão de Recursos: O agente possui energia limitada e precisa gerenciar um inventário (extintores, chaves) para superar obstáculos.
Lógica de Busca: O sistema avalia rotas alternativas e condições ambientais (fumaça, portas trancadas) em tempo real para garantir a sobrevivência do indivíduo.

## 🚀 Tecnologias Utilizadas
Linguagem: Python 3.
Paradigma: Programação Estruturada
Estruturas de Dados: Listas aninhadas, Dicionários e Controle de Fluxo Avançado (match-case).
Ambiente: Jupyter Notebook / Google Colab.

##📊 Funcionalidades e Algoritmos

##🌡️ Algoritmo de Conforto Urbano
O sistema utiliza uma função de penalidade linear para calcular o bem-estar térmico:
Temperatura Ideal: 22°C (desvios geram penalidade de 0.25 pts por grau).
Umidade Ideal: Entre 60% e 70%.
IQA: Normalização de dados poluentes para escala de 0 a 3 pontos de penalidade.

## 🏃 Lógica de Evacuação
Sistema de Obstáculos: Implementação de nós (nodes) com estados variados.
Tomada de Decisão: O agente prioriza a rota principal, mas é capaz de realizar o backtracking ou desvio para rotas laterais caso encontre barreiras intransponíveis (como portas trancadas sem chave).

## 🔧 Como Executar
1. Abra o arquivo .ipynb em um ambiente compatível.
2. Certifique-se de ter o Python instalado ou utilize o Google Colab.
3. Execute as células para visualizar o output formatado das análises e da simulação.

---
[Voltar ao Início](https://github.com/viniciusravini-hub/portfolio-vinicius-passos/tree/main)
