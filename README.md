# Turismo-no-Brasil---1995-vs.-1996
Este projeto foi elaborado com base em conjuntos de dados disponibilizados pelo Ministério do Turismo no link: https://dados.gov.br/dados/organizacoes/visualizar/ministerio-do-turismo, com o objetivo de analisar como ocorreu o movimento de turistas vindos do exterior durante os Carnavais de 1995 e 1996, focando nas seguintes perguntas de negócio:
> De onde veio a maioria dos turistas a cada ano?
> Quais os destinos mais populares?
> Quais as três vias de acesso mais populares? 
> Quais os meses em que São Paulo recebeu mais turistas fora do Carnaval em 1995? E em 1996?
> Qual a via de acesso menos popular entre aqueles que visitaram o sul do Brasil?

Após a elaboração de um "rascunho" no MySQL Workbench, o script foi refinado no BigQuery para que fosse possível importar as duas bases de dados para o Looker Studio como um único arquivo.
 
Por fim, o arquivo .csv foi utilizado como base de dados no data studio, dando origem ao relatório, que respondeu às perguntas de negócio através de tabelas e gráficos de pizza, mapas, barras e contadores.
