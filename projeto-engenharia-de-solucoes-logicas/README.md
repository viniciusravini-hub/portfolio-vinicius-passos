# 🛒 Sistema Automatizado de Vendas e Análise de Risco

## 📝 Descrição do Projeto
Este projeto consiste em uma ferramenta de automação para o processamento de transações comerciais, integrando análise estatística simples e protocolos de segurança cibernética. O sistema foi desenvolvido para atuar como um middleware de validação, capaz de calcular médias de desempenho e identificar anomalias transacionais em tempo real.

O foco principal é a **segurança operacional**, utilizando estruturas de decisão lógica para colocar o sistema em "quarentena" ou solicitar "revisão manual" sempre que um comportamento fora do padrão (outlier) é detectado, garantindo a integridade financeira do fluxo de vendas.

## 🚀 Funcionalidades
* **Cálculo de Média Dinâmica:** Processamento automático da média aritmética de lotes de vendas.
* **Protocolo de Segurança Ativo:** Monitoramento de legitimidade com bloqueio preventivo (Quarentena).
* **Detecção de Anomalias (Outliers):** Identificação automática de vendas que excedem em 5x a média do lote, disparando alerta de revisão manual.
* **Gestão de Limites:** Interface interativa para ajuste dinâmico do `LIMITE_DE_SEGURANÇA` em caso de detecção de irregularidades.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3.x
* **Ambiente:** Google Colab / CLI (Interface de Linha de Comando)
* **Paradigma:** Programação Estruturada

## 📊 Estrutura de Validação (Lógica de Negócio)
O sistema opera baseado em três cenários críticos de decisão:

| Cenário | Condição | Ação do Sistema |
| :--- | :--- | :--- |
| **Normalidade** | Venda legítima e abaixo do limite | Transação Aprovada |
| **Risco Elevado** | Venda não legítima + Média > Limite | **SISTEMA EM QUARENTENA** |
| **Anomalia de Valor** | Venda > 5x a Média | **REVISÃO MANUAL** |


   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
