Vídeo de apresentação do projeto:
https://www.loom.com/share/426c81010d8f40feba6478ea9962c20b?sid=50733878-e551-4286-bcf9-882ef3119715
(O vídeo ficou muito grande para que pudéssemos passar por tudo que foi feito, recomendamos colocar em 1.5x ou 2x)

Ou, pode acessar o vídeo já acelerado em sua versão de 20 minutos:
https://drive.google.com/file/d/1PuG0U-PRgzDRA7SUDClmW393KGG522a-/view?usp=sharing


# Ciência de Dados Premier League 23/24 - Primeira Entrega

Para a primeira entrega do projeto da disciplina de Gerenciamento de Dados e Informação, realizamos uma análise dos dados de todos os jogadores que atuaram na úlitma Premier League (primeira divisão do futebol inglês).
Para isso, retiramos os dados do site SofaScore, utilizando Selenium. 
Exploramos as relações entre várias métricas de desempenho como gols, assistências, dribles bem-sucedidos, desarmes e porcentagem de passes precisos para identificar padrões e outliers.

## Etapas
- Configuração Inicial: Configuração do ambiente com Selenium, Google Chrome e ChromeDriver para automação web.
- Coleta de Dados: Utilização de Selenium para interagir com elementos web e extrair dados de performance do jogador diretamente dos logs do navegador.
- Pré-processamento dos Dados: Limpeza de dados para remover valores ausentes ou incoerentes, e transformação de variáveis categóricas.
- Análise Exploratória: Inclui visualizações como histogramas e boxplots para entender a distribuição dos dados e identificação de outliers.
- Remoção de Outliers: Aplicação das técnicas Z-score robusto, Método de Tukey, Elliptic Envelope e  Isolation Forest para limpar os dados de valores extremos.
- Discretização: Técnicas aplicadas para transformar variáveis contínuas em categóricas.
- Testes de Hipótese: Avaliação de associações estatísticas entre diferentes variáveis para validar hipóteses específicas sobre os dados.

## Principais biblotecas utilizadas

- `selenium`: Para automação de navegação web e coleta de dados.
- `pandas` e `numpy`: Para manipulação e análise de dados.
- `scipy` e `sklearn`: Para aplicação de técnicas estatísticas e de machine learning.
- `matplotlib` e `seaborn`: Para visualização de dados.


# Ciência de Dados Premier League 23/24 - Segunda Entrega
Na segunda entrega do projeto da disciplina de Gerenciamento de Dados e Informação, avançamos para a modelagem preditiva, explorando o impacto de várias métricas de desempenho no rating dos jogadores da última Premier League. Utilizamos ferramentas avançadas como scikit-learn e H2O para automação de machine learning, além de técnicas de visualização para entender melhor as relações entre as variáveis.

## Etapas 

- Instalação de Bibliotecas: Configuração do ambiente com instalação de bibliotecas necessárias para aprendizado de máquina, manipulação de dados e visualização.
- Divisão dos Dados: Os dados foram divididos em conjuntos de treinamento, validação e teste para uma avaliação robusta dos modelos.
- Seleção e Configuração dos Modelos: Definimos quatro tipos de modelos de regressão e configuramos uma grade de hiperparâmetros para cada um usando o GridSearchCV.
- Treinamento e Avaliação dos Modelos: Cada modelo foi treinado e avaliado utilizando o GridSearchCV, e os resultados foram registrados usando MLFlow.
- AutoML do H2O: Utilizamos o H2O AutoML para automação do processo de modelagem, simplificando a seleção e otimização dos modelos.
- Teste e Diagnóstico do Melhor Modelo: Comparação dos modelos utilizando o conjunto de teste e análise visual dos resíduos para diagnosticar problemas potenciais.

## Principais bibliotecas utilizadas

- `h2o`: Para automação de machine learning.
- `scikit-learn`: Para modelagem preditiva e avaliação.
- `pandas` e `numpy`: Para manipulação e análise de dados.
- `matplotlib` e `seaborn`: Para visualização de dados.
- `mlflow`: Para rastreamento de experimentos

## Autores

- Guilherme Ribeiro - grcc@cin.ufpe.br
- Luiza Diniz - ldmml@cin.ufpe.br
