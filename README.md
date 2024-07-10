Vídeo de apresentação do projeto: https://www.loom.com/share/426c81010d8f40feba6478ea9962c20b?sid=50733878-e551-4286-bcf9-882ef3119715
(O vídeo ficou muito grande para que pudéssemos passar por tudo que foi feito, recomendamos colocar em 1.5x ou 2x)


# Ciência de Dados Premier League 23/24

Para a primeira entrega do projeto da disciplina de Gerenciamento de Dados e Informação, realizamos uma análise dos dados de todos os jogadores que atuaram na úlitma Premier League (primeira divisão do futebol inglês).
Para isso, retiramos os dados do site SofaScore, utilizando Selenium. 
Exploramos as relações entre várias métricas de desempenho como gols, assistências, dribles bem-sucedidos, desarmes e porcentagem de passes precisos para identificar padrões e outliers.

# Etapas
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

## Autores

- Guilherme Ribeiro - grcc@cin.ufpe.br
- Luiza Diniz - ldmml@cin.ufpe.br
