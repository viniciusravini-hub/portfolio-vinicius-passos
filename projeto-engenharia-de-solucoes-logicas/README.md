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

```portugol
// Exemplo de trecho do algoritmo
Algoritmo OtimizadorSemaforo
Inicio
    Enquanto (sistema_ativo) faca
        sensor_vias = ler_sensores()
        Se (sensor_vias > densidade_limite) entao
            priorizar_via_congestonada()
        Senao
            manter_ciclo_padrao()
        FimSe
    FimEnquanto
Fim
```
---
[Voltar ao Início](https://github.com/viniciusravini-hub/portfolio-vinicius-passos/tree/main)
