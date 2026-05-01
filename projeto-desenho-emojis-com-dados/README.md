# 🎨🐍 Manipulação de Estruturas de Dados: Emojis & Matrizes Musicais

## 📝 Descrição do Projeto
Este repositório contém uma série de desafios de programação em Python focados na manipulação avançada de estruturas de dados multidimensionais (listas, dicionários e tuplas). O projeto simula o processamento de imagens (pixels RGB) e a transposição de matrizes de áudio, demonstrando o uso de lógica de programação para transformar dados brutos em informações processadas.

Desenvolvido como parte de um estudo prático de **Lógica de Programação e Estruturas de Dados**, o código explora a iteração em múltiplos níveis (nested loops) e a aplicação de filtros matemáticos em matrizes.

---

## 🛠️ Funcionalidades e Desafios

O projeto está dividido em três etapas principais de processamento:

1.  **Filtro de Sombra em Emojis:** * Varredura de uma grade de pixels RGB (tuplas imutáveis).
    * Aplicação de um filtro de sombreamento dividindo os valores de cor por 2, mantendo a integridade de elementos específicos (olhos e boca).
2.  **Transposição de Matrizes Musicais:**
    * Processamento de uma biblioteca musical contendo frequências em matrizes $2 \times 2$.
    * Implementação de lógica de transposição ($A_{ij} \to A_{ji}$) para inverter linhas e colunas dos tons musicais.
3.  **Integrador - Playlist de Imagens:**
    * Um motor de processamento que une conceitos de imagem e áudio.
    * Uso de métodos específicos de Python como `.pop()`, `.insert()`, `.keys()` e `.update()`.
    * Filtro condicional de brilho baseado em canais de cor.

---

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.x
* **Ambiente:** Jupyter Notebook / Google Colab
* **Conceitos Chave:**
    * Matrizes Multidimensionais
    * Manipulação de Tuplas (Imutabilidade)
    * List Comprehension e Loops Aninhados (3 níveis)
    * Métodos de Dicionários e Listas

---

## 📊 Resultados e Aprendizados
O projeto demonstra a capacidade de manipular dados complexos sem o uso de bibliotecas externas (como NumPy), focando puramente na lógica nativa da linguagem:
* **Manipulação de Tuplas:** Aprendizado sobre a necessidade de criar novas instâncias de tuplas ao realizar modificações em dados RGB.
* **Lógica de Matriz:** Sucesso na implementação de transposição manual, essencial para entender o funcionamento de processamento de sinais e imagens.
* **Gestão de Memória:** Uso eficiente de métodos de lista para inserção e remoção de itens em tempo de execução.

---

## 🔧 Como Executar
1. Certifique-se de ter o Python instalado ou utilize o Google Colab.
2. Abra o arquivo Untitled3.ipynb em seu ambiente de preferência.
3. Execute as células sequencialmente para visualizar os estados das grades e matrizes antes e depois do processamento.

---
