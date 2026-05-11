# customer-churn-dataprep

Este projeto foca na etapa primordial de um pipeline de Ciência de Dados: a **Preparação de Dados**. O objetivo principal é transformar dados brutos de uma empresa de telecomunicações, fornecidos em formato JSON aninhado, em um conjunto de dados limpo, normalizado e pronto para a aplicação de algoritmos de Machine Learning.

O foco central aqui é o tratamento de dados de *Churn* (evasão de clientes), permitindo análises futuras sobre por que os clientes deixam a empresa.

## Estrutura do Repositório

* `dataprep_churn.ipynb`: Jupyter Notebook contendo todo o fluxo de ETL (Extract, Transform, Load) e limpeza dos dados.
* `dataset-telecon.json`: Conjunto de dados bruto contendo informações demográficas, serviços assinados e detalhes financeiros dos clientes.

## Tecnologias Utilizadas

* **Python 3.10+**
* **Pandas**: Manipulação e análise de dados.
* **JSON Library**: Suporte para carregamento de arquivos estruturados.

## Etapas de Desenvolvimento

O notebook segue uma estrutura lógica de engenharia de dados:

1.  **Carregamento e Normalização**: Tratamento de campos JSON aninhados (nested) para transformá-los em colunas tabulares.
2.  **Análise Exploratória Inicial (EDA)**: Identificação de tipos de dados, valores nulos e inconsistências.
3.  **Limpeza de Dados**:
    * Tratamento de strings vazias e valores nulos.
    * Conversão de tipos de dados (ex: strings para float em campos financeiros).
    * Remoção de duplicatas.
4.  **Transformação**: Preparação inicial de variáveis para facilitar a modelagem estatística futura.

## Como Executar

- Clone o repositório:

   ```bash
    git clone https://github.com/ghfreiree/customer-churn-dataprep.git
   
---
*Desenvolvido com dedicação para aprofundamento em Data Science*
