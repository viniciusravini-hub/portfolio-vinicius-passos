# 🛒 Sistema Automatizado de Vendas e Análise de Risco

Este projeto apresenta uma solução algorítmica para a gestão inteligente de tráfego urbano. O objetivo principal é a redução de congestionamentos através do ajuste dinâmico de tempos de semáforo, partindo de uma abstração visual (fluxograma) até a validação lógica (teste de mesa).

---

## 📌 Visão Geral do Projeto
A gestão eficiente do tráfego é um dos pilares das **Cidades Inteligentes**. Este algoritmo processa dados de sensores de presença e densidade veicular para decidir, em tempo real, a prioridade de abertura de vias, visando otimizar o fluxo e reduzir o tempo de espera.

## 🛠️ Desenvolvimento e Metodologia
O projeto foi estruturado em quatro etapas principais:

### 1. Modelagem Visual (Fluxograma)
A lógica da solução foi desenhada para contemplar as entradas de sensores e múltiplos pontos de decisão.
* **Elementos inclusos:** Sensores de densidade, cálculos de temporização e estruturas condicionais de segurança.

### 2. Estruturação Lógica (Pseudocódigo)
Tradução do fluxo para a linguagem **Portugol**, utilizando estruturas de repetição (`enquanto`) e condicionais (`se/então/senão`).

---

## 🚀 Funcionalidades
* **Cálculo de Média Dinâmica:** Processamento automático da média aritmética de lotes de vendas.
* **Protocolo de Segurança Ativo:** Monitoramento de legitimidade com bloqueio preventivo (Quarentena).
* **Detecção de Anomalias (Outliers):** Identificação automática de vendas que excedem em 5x a média do lote, disparando alerta de revisão manual.
* **Gestão de Limites:** Interface interativa para ajuste dinâmico do `LIMITE_DE_SEGURANÇA` em caso de detecção de irregularidades.

## 📊 Estrutura de Validação (Lógica de Negócio)
O sistema opera baseado em três cenários críticos de decisão:

| Cenário | Condição | Ação do Sistema |
| :--- | :--- | :--- |
| **Normalidade** | Venda legítima e abaixo do limite | Transação Aprovada |
| **Risco Elevado** | Venda não legítima + Média > Limite | **SISTEMA EM QUARENTENA** |
| **Anomalia de Valor** | Venda > 5x a Média | **REVISÃO MANUAL** |

---
[Voltar ao Início](https://github.com/viniciusravini-hub/portfolio-vinicius-passos/tree/main)
