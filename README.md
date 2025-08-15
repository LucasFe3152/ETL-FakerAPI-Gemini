# ETL-FakerAPI-Gemini
### Pipeline de ETL com Faker API e Gemini

Este projeto é uma **pipeline de ETL (Extração, Transformação e Exportação)** que demonstra a integração de diferentes APIs para processar e enriquecer dados. Ele foi desenvolvido como parte do aprendizado obtido no **bootcamp da Santander Dev Week 2023**, aprofundando o conceito de pipelines de dados e a utilização de ferramentas modernas para automação e análise.

### Visão Geral do Projeto

A pipeline opera em um fluxo sequencial, executando as seguintes etapas:

#### 1. Extração de Dados
Os dados brutos são extraídos da **Faker API**, que simula perfis de usuários com informações como nome completo, data de nascimento, cidade e país. Essa etapa é crucial para obter um conjunto de dados inicial com o qual trabalhar, imitando um cenário real de coleta de dados de usuários.

#### 2. Transformação e Enriquecimento
Esta é a etapa central do projeto. Após a extração, os dados de cada perfil são transformados. Uma solicitação é enviada à **API do Gemini** com os dados de nome, idade, cidade e país do usuário. O modelo de IA é então utilizado para gerar e retornar **três recomendações de filmes** personalizadas, agregando valor significativo aos dados brutos.

#### 3. Exportação de Dados
Finalmente, os dados originais, agora enriquecidos com as recomendações de filmes, são exportados para um arquivo no formato **CSV**. O arquivo de saída é ideal para ser usado em outras aplicações, como ferramentas de análise de dados, visualizações ou futuros projetos de machine learning.

Este projeto é um exemplo prático de como orquestrar a coleta de dados de múltiplas fontes e usar a inteligência artificial para agregar valor a essas informações. Ele serve como uma base sólida para quem deseja explorar pipelines de dados e a integração de modelos de linguagem em fluxos de trabalho de processamento, seguindo a metodologia de projeto de dados do bootcamp da Santander Dev Week.
