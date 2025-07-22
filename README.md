# Projetos Datacamp

Coleção de projetos que realizei no [__Datacamp__](https://app.datacamp.com/learn) durante as trilhas de Eng. de dados, Cientista de Dados e Analista de dados.

- [__Data Science Associate: Previsão de Preços de Imóveis com Scikit-learn e Pandas__](https://github.com/marcodelph/datacamp/tree/main/Project%3A%20Data%20Scientist%20Associate%20Practical%20Exam)
  
  Neste projeto, desenvolvi um modelo preditivo de ponta a ponta para otimizar a precificação de imóveis e acelerar o tempo de venda. O trabalho abrange o ciclo completo de um problema de regressão: partindo de dados brutos, realizei uma rigorosa limpeza, tratamento de valores nulos e padronização de features. Para a predição, implementei e comparei uma Regressão Linear (baseline) e um Random Forest, demonstrando a aplicação de diferentes algoritmos para resolver um desafio de negócio real e aumentar a competitividade da empresa.
  
  **Principais Competências e Tecnologias:** Python, Pandas, Scikit-learn, Análise Exploratória de Dados (EDA), Limpeza de Dados, Engenharia de Features, Modelagem Preditiva (Regressão).

 - [__AI Engineer: Previsão de Compra de Clientes com PyTorch e Pandas__](https://github.com/marcodelph/datacamp/tree/main/Project%3A%20AI%20Engineer%20for%20Data%20Scientists%20Associate%20Practical%20Exam)

  Este projeto demonstra a construção de um sistema de previsão de compras de ponta a ponta. O processo inicia com a limpeza de dados brutos, tratando valores ausentes com estratégias de imputação (mediana, média). Em seguida, as features são preparadas para o modelo através de normalização (Min-Max scaling) e codificação (one-hot encoding). Por fim, uma rede neural é construída e treinada com PyTorch para classificar se um cliente irá ou não realizar uma compra, aplicando o modelo treinado para fazer previsões em um conjunto de validação.

  **Principais Competências e Tecnologias:** Python, Pandas, Scikit-learn, PyTorch, Limpeza de Dados, Engenharia de Features, Redes Neurais, Modelagem de Classificação.

  - [__Engenharia de Dados: Pipeline de Limpeza e Unificação de Dados de Saúde__](https://github.com/marcodelph/datacamp/tree/main/Data%20Engineer%20Certification%20-%20Practical%20Exam%20-%20Supplement%20Experiments)

  Este projeto resolve um desafio de engenharia de dados ao centralizar quatro fontes de dados distintas (perfis de usuário, métricas de saúde, uso de suplementos e metadados de experimentos) em um único dataset coeso e pronto para análise. Desenvolvi uma função em Python que automatiza todo o processo de ETL (Extração, Transformação e Carga): realizando a junção estratégica das tabelas, tratando valores ausentes, convertendo unidades (mg para gramas), extraindo valores numéricos de strings e criando novas features, como faixas etárias, para enriquecer a análise.

  **Principais Competências e Tecnologias:** Python, Pandas, Engenharia de Dados, Limpeza e Transformação de Dados (Data Wrangling), Integração de Dados.

  - [__SQL: Análise e Limpeza de Dados com SQL Avançado em PostgreSQL__](https://github.com/marcodelph/datacamp/tree/main/Analyzing%20and%20Formatting%20PostgreSQL%20Sales%20Data)

  Neste projeto, utilizei SQL avançado para realizar tarefas de limpeza e análise em um banco de dados PostgreSQL de uma grande loja. Desenvolvi duas consultas complexas para resolver desafios comuns de dados: a primeira utiliza Funções de Janela (Window Functions) e CTEs para calcular e rankear os 5 produtos mais vendidos em cada categoria. A segunda implementa uma lógica de imputação para preencher valores de quantidade ausentes, calculando um preço unitário estimado com base em dados históricos para garantir a integridade do dataset.

  **Principais Competências e Tecnologias:** SQL, PostgreSQL, Limpeza de Dados, Análise de Dados, Funções de Janela (Window Functions), CTEs (Common Table Expressions), Imputação de Dados.

  - [__Análise de Investimentos com SQL: Identificando Setores de Unicórnios em Alta__](https://github.com/marcodelph/datacamp/tree/main/Analyzing%20Unicorn%20Companies)

  Este projeto de análise de dados fornece insights para uma firma de investimentos sobre tendências em empresas de alto crescimento (unicórnios). Utilizando uma consulta SQL avançada, identifiquei as três indústrias com o maior número de novos unicórnios entre 2019 e 2021. A consulta, estruturada com Expressões de Tabela Comuns (CTEs), primeiro isola os setores de melhor performance e, em seguida, calcula o número de novas empresas e a média de sua avaliação (valuation) para cada ano, permitindo uma visão clara sobre a evolução e o potencial de cada setor.

  **Principais Competências e Tecnologias:** SQL, Análise de Dados, Análise de Investimentos, CTEs (Common Table Expressions), Agregação de Dados.

- [__Controle de Qualidade em Manufatura com SQL Avançado__](https://github.com/marcodelph/datacamp/tree/main/Evaluate%20a%20Manufacturing%20Process)

  Neste projeto, desenvolvi um sistema de monitoramento para controle de qualidade em um processo de manufatura, aplicando os princípios do Controle Estatístico de Processo (SPC). Utilizando Funções de Janela (Window Functions) em SQL, criei uma consulta que calcula dinamicamente os limites de controle superior (UCL) e inferior (LCL) para a altura de um produto, com base em uma janela móvel das últimas cinco medições por operador. O sistema gera um alerta booleano sempre que uma peça excede esses limites, permitindo a identificação imediata de desvios no processo.

  **Principais Competências e Tecnologias:** SQL, PostgreSQL, Funções de Janela (Window Functions), CTEs, Análise de Qualidade.

  - [__Análise de Dados para ONGs com SQL Avançado__](https://github.com/marcodelph/datacamp/tree/main/Impact%20Analysis%20of%20GoodThought%20NGO%20Initiatives)

  Neste projeto de análise de dados, desenvolvi consultas SQL para a ONG "GoodThought" para extrair insights sobre a performance e o financiamento de seus projetos. A primeira consulta identifica os cinco projetos com maior arrecadação, agregando o total de doações por tipo de doador para entender as principais fontes de financiamento. A segunda consulta é mais complexa, utilizando Funções de Janela (Window Functions) e CTEs para determinar o projeto de maior impacto em cada região geográfica, garantindo que apenas projetos que receberam doações fossem considerados.

  **Principais Competências e Tecnologias:** SQL, PostgreSQL, Análise de Dados, Funções de Janela (Window Functions), CTEs (Common Table Expressions), Agregação de Dados.

- [__Análise e Limpeza de Catálogo de Produtos com SQL__]([INSERIR LINK AQUI])

  Este projeto aborda um ciclo completo de preparação e análise de dados para a rede de supermercados "FoodYum". Utilizando SQL, iniciei com uma avaliação da qualidade dos dados para identificar a quantidade de valores ausentes em colunas críticas. Em seguida, desenvolvi uma consulta de limpeza abrangente para tratar os dados faltantes com base em regras de negócio específicas — como imputar medianas, valores padrão ou a string "Unknown" — e para padronizar formatos. Por fim, realizei uma análise exploratória para agregar e extrair insights, como a faixa de preço (mínimo e máximo) para cada categoria de produto.

  **Principais Competências e Tecnologias:** SQL, PostgreSQL, Limpeza de Dados (Data Cleaning), Análise Exploratória de Dados (EDA), Agregação de Dados.


