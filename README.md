# Projeto de Data Harvesting e Análise de Letras de Músicas

Este projeto foi desenvolvido como parte da disciplina de pós-graduação em Ciência de Dados. O objetivo principal é realizar o data harvesting (coleta de dados) de letras de músicas de um site específico e, posteriormente, realizar uma análise não supervisionada para entender padrões e comportamentos das músicas coletadas. Como o processo de raspagem mostrou-se demorado mesmo em máquinas eficientes, foi criado um arquivo .csv para salvar as informações

## Objetivos

- Coletar letras de músicas de um site de letras de músicas.
- Limpar e pré-processar os dados coletados.
- Aplicar técnicas de análise não supervisionada para identificar padrões nas letras das músicas.

## Tecnologias Utilizadas

- **Linguagem de Programação:** Python
- **Bibliotecas Principais:**
  - `pandas`: Para manipulação e análise de dados.
  - `Selenium`: Para coleta de dados (web scraping). Mostrou-se mais eficaz, dado que há um carregamento assincrono
  - `scikit-learn`: Para técnicas de análise não supervisionada, sendo essas Clusterização e t-SNE. Além disso, foi usado para extração de Features de texto.
  - `matplotlib`: Para visualização de dados.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
