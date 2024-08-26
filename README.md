# Projeto de Previsão de Inatividade em Corredores Amadores
---

Bem-vindo! 

Esse é o repositório onde estão todos os códigos do projeto. Nele, são utilizados modelos preditivos para identificar corredores amadores que estão prestes a entrar em períodos de inatividade. Com base nessas previsões, é possível adotar estratégias para ajudar o atleta a manter-se constante nos treinos. 

Os modelos foram treinados com dados de corrida coletados de diversas fontes, incluindo Garmin, Strava, Nike Run e Fitbit.

O Storytelling do projeto pode ser encontrado no [Medium](https://medium.com/@matheussmelo/keep-running-prevendo-inatividade-de-corredores-amadores-para-poder-ajud%C3%A1-los-a-continuar-correndo-2d71b0f5c8b4).

## Pastas
---

1. A pasta [main_pipeline](https://github.com/matheussmelo/running_inactivity_prediction/tree/main/main_pipeline) possui a estrutura de arquivos principal do projeto, onde:

1.1. [Pré-processamento](https://github.com/matheussmelo/running_inactivity_prediction/blob/main/main_pipeline/1.%20Pre-processing.ipynb): Essa etapa serviu para extração dos dados em diferentes formatos de arquivos (.json, .gpx, .fit e .json) e a criação de todas as features que fizeram parte do modelo.

1.2. [Análise exploratória dos dados](https://github.com/matheussmelo/running_inactivity_prediction/blob/main/main_pipeline/2.%20EDA.ipynb): Essa etapa serviu para analisar e explorar as features criadas em busca de informações valiosas que pudessem auxiliar nos modelos preditivos a ser criados.

1.3. [Modelagem](https://github.com/matheussmelo/running_inactivity_prediction/blob/main/main_pipeline/3.%20Modeling.ipynb): Essa etapa serviu para mostrar todas as etapas adotas na modelagem principal, abordando a seleção das features, algoritmos utilizados, criação e validação dos modelos preditivos e análise dos resultados.

* Na etapa 3 foram obtidos 3069 modelos diferentes gerados a partir de diferentes combinações entre as diferentes features e algoritmos. Sendo assim, os resultados foram atribuidos à uma tabela [Excel](https://github.com/matheussmelo/running_inactivity_prediction/blob/main/main_pipeline/models_results.xlsx).

2. Já a pasta [file_formats_tests](https://github.com/matheussmelo/running_inactivity_prediction/tree/main/file_formats_tests) apresenta os arquivos de teste para demonstrar o pré-processamento feito no Arquivo 1.1 com cada um dos formatos de arquivos .json, .gpx, .fit e .tcx (neste especificamente há um arquivo extra que serve para formatar os arquivos em uma estrutura XML correta, caso não estejam).

Espero que goste!
