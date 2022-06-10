# Desafio-SmarttLab

O projeto consiste em um processo de “ETL” (extract, transform, load) com análise descritiva de três datasets referentes a dados da Ibovespa e de rôbos traders. Os arquivos foram extraídos e transformados com a biblioteca Pandas, para analisar os dado fiz uso da API SPARK integrada ao Python (Pyspark) e também a instalei bibliotecas para produção de gráficos, assim gerar insights. A visualização dos dados foi realizada no Power BI  

Objetivo: Avaliação de habilidades na área de análise e estudo estatístico de dados.

1) Instruções

Parte I

a. Realize uma análise estatística descritiva dos dados do Ibovespa
(“Dados_Ibovespa”).

b. Utilizando tabelas e/ou gráficos, identifique informações relevantes que podem
ser extraídas dos dados.

c. Faça uma breve conclusão para o estudo realizado

Parte II

a. Realize uma análise estatística descritiva dos dados dos robôs (“Robos_resultado”
e “Robos_trade”).

b. Utilizando tabelas e/ou gráficos, crie métricas para avaliação dos robôs.

c. Faça um ranking com os 5 melhores robôs de acordo com sua análise.

2) Descrição dos Dados

a) Dados_Ibovespa: histórico de dados diários dos valores do índice Bovespa

i) Data: dia do pregão

ii) Último: último valor negociado no dia

iii) Abertura: primeiro valor negociado no dia

iv) Máxima: maior valor de negociação no dia

v) Mínima: menor valor de negociação no dia

vi) Vol: volume de negociação do dia

vii) Var%: Variação percentual em relação ao dia anterior

b) Robos_resultado: resultado financeiro diário de robôs a serem analisados

i) Date: dia analisado

ii) Outras colunas: ID de cada robô da análise

iii) Células: resultado diário financeiro para cada robô

c) Robos_trade: número de operações realizadas pelos robôs por dia

i) Date: dia analisado

ii) Outras colunas: ID de cada robô da análise (idem “Robos_resultado’)

iii) Células: número de operações diárias realizado por cada robô

3) Ferramentas:

Trello

Google Drive

Google Colab

Power BI

4) Bibliotecas:

Python

Pandas

Apache Spark

seaborn

matplotlib

