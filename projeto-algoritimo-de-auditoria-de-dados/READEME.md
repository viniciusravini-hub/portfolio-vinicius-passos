# 🛒 Sistema Automatizado de Análise de Vendas

## 📝 Descrição do Projeto
Este projeto consiste em um script interativo desenvolvido em Python para o monitoramento, validação e análise de transações. O objetivo principal é atuar como uma camada de segurança primária, calculando métricas em lote e aplicando regras de negócio para prevenir fraudes, bloquear valores suspeitos e alertar sobre anomalias.

Originalmente estruturado no Google Colab, o sistema processa entradas de vendas e utiliza condicionais lógicas rigorosas. Dependendo da avaliação de legitimidade do usuário e do desvio padrão das vendas em relação à média, o programa pode atualizar os limites de segurança dinamicamente, colocar o sistema em "quarentena" ou disparar um alerta para "revisão manual".

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Ambiente de Desenvolvimento:** Google Colab / Jupyter Notebook
* **Bibliotecas:** Nenhuma dependência externa (uso exclusivo de bibliotecas padrão do Python)

## 📊 Funcionalidades e Aprendizados
O projeto estabelece uma base sólida para lógicas de sistemas anti-fraude e validação de transações:

* **Detecção de Anomalias (Spikes):** O algoritmo aciona automaticamente uma flag de **REVISÃO MANUAL** caso uma única transação seja 5 vezes superior à média das vendas atuais.
* **Sistema de Quarentena:** Implementação de um bloqueio preventivo ativado se uma venda for sinalizada como ilegítima e a média ultrapassar o limite de segurança estabelecido.
* **Limites de Segurança Dinâmicos:** Permite a redefinição do limite de segurança em tempo de execução com base na análise de risco da transação em andamento.
* **Tratamento de Dados e Validação:** Uso prático de laços de repetição (`while`) para garantir validação contínua de input do usuário e funções que manipulam o escopo de variáveis globais (`global`).

## 🔧 Como Executar

1. Faça download do arquivo 'untitled0.py'.
2. Abra o arquivo em um ambiente compatível (Google Colab ou VS Code).
3. Execute a célula de código principal
4. Digite os valores para a Venda 1, Venda 2 e Venda 3 no terminal integrado para interagir com o sistema.

---
(Voltar ao Início)[[https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/viniciusravini-hub/portfolio-vinicius-passos/tree/main)]
