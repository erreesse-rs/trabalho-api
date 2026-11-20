# Dashboard Comics Universe

Este projeto propõe a análise de 1.000 personagens dos universos Marvel e DC Comics.

Por meio do dashboard desenvolvido, é possível identificar os personagens com maior número de aparições e analisar a representatividade de cada um em relação ao total de publicações. A análise também abrange:

- **Perfil dos personagens:** origem e gênero;
- **Universo e narrativa:** poderes, equipes, criadores e os principais conceitos ou temas presentes nas histórias.

Todas essas métricas podem ser exploradas dinamicamente por meio de filtros por **editora**, **gênero**, **origem** e **quantidade de aparições**.

## Como visualizar o dashboard

O dashboard pode ser acessado pelo link: [https://marveldcdashboard.oneapp.dev/](https://marveldcdashboard.oneapp.dev/)

Para utilizá-lo, basta fazer o upload do arquivo `base_dashboard_marvel_dc.xlsx`, disponível neste repositório.

## Construção do projeto

- **Extração e tratamento dos dados:** realizados no Google Colab, com os códigos e suas respectivas explicações disponíveis neste projeto.
- **Tradução e sintetização dos dados:** após o tratamento dos dados, o arquivo `.xlsx` foi traduzido com o apoio do Gemini.
- **Desenvolvimento do dashboard:** construído em HTML, proporcionando maior liberdade de estruturação e design.
