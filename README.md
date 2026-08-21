# Monitoramento de Queimadas: Machine Learning & Visão Computacional

Projeto interno focado no processamento, análise e modelagem preditiva de dados de focos de queimadas e dados orbitais.

---

## Guia de Pastas e Estrutura

* **`data/`**: Armazena a base de dados do projeto.
  * **`data/raw/`**: Dados brutos baixados diretamente do INPE ou fontes externas. **Nunca** altere estes arquivos manualmente.
  * **`data/processed/`**: Dados limpos, filtrados e preparados para os modelos.
* **`notebooks/`**: Rascunhos e testes em Jupyter Notebook (`.ipynb`) para análises exploratórias, gráficos e prototipagem rápida.
* **`src/`**: Código-fonte oficial do projeto em scripts Python (`.py`). Contém o processamento de dados, pipelines de treino e funções reutilizáveis.
* **`models/`**: Guarda os arquivos dos modelos treinados e salvos (`.pt`, `.pkl`, `.h5`) para reutilização.
* **`docs/`**: Documentação complementar, como diagramas da arquitetura, relatórios e imagens do projeto.

---

## Arquivos da Raiz

* **`requirements.txt`**: Lista com todas as bibliotecas necessárias para rodar o projeto no mesmo ambiente.
* **`README.md`**: Guia principal com explicações do projeto, instruções de uso e membros da equipe.
* **`.gitignore`**: Define quais arquivos e pastas pesadas (como bases de dados) o Git deve ignorar.
