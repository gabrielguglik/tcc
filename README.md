# Um Estudo Comparativo sobre o Uso de LLMs na Criação de Testes de Integração de Software

Este repositório contém os conjuntos de dados (brutos e tratados) utilizados como base empírica para o Trabalho de Conclusão de Curso (TCC) no curso de Sistemas de Informação. O estudo avalia e compara o desempenho de diferentes *Large Language Models* (LLMs) no contexto de qualidade de software.

## 📂 Estrutura dos Arquivos

Os dados estão organizados nos seguintes arquivos no formato CSV:

* **`Dados dos Artigos (tratados).csv`**: Base de dados resultante da Revisão Sistemática da Literatura (com buscas executadas originalmente no segundo semestre de 2025). Contém o mapeamento e a extração de dados dos estudos primários selecionados.
* **`Execução dos Prompts - DeepSeek-V4-Flash.csv`**: Resultados detalhados das inferências realizadas utilizando o modelo DeepSeek.
* **`Execução dos Prompts - Gemini 2.5 Pro.csv`**: Resultados das inferências realizadas utilizando o modelo Gemini via endpoint oficial.
* **`Execução dos Prompts - GPT-5.4.csv`**: Resultados das inferências realizadas utilizando o modelo GPT.

## 🔬 Metodologia de Coleta

Os dados de execução documentados neste repositório foram gerados a partir de interações com os modelos citados utilizando a técnica de *one-shot prompting*, fornecendo um exemplo estruturado para guiar a saída das IAs. 

Visando um maior controle sob as variáveis e respostas, as requisições foram conduzidas e validadas de forma manual através de clientes de API, garantindo a integridade do retorno antes da tabulação dos resultados.

## 👨‍💻 Autor

* **Gabriel Guglielmi Kirtschig**

*Nota: Este repositório tem fins estritamente acadêmicos, atuando como apêndice digital para garantir a transparência e a reprodutibilidade da pesquisa.*
