## Instruções

Bases:

Tweets anotados - https://github.com/andrecristiani/analise-de-sentimentos-eleicoes-2018/blob/master/SepararPoliticos%20-%20Primeiro%20Turno/DadosAnotados.csv

Tweets 2º Turno Bolsonaro: https://github.com/andrecristiani/analise-de-sentimentos-eleicoes-2018/blob/master/SepararPoliticos%20-%20Segundo%20turno/listBolsonaro.csv

Tweets 2º Turno Haddad: https://github.com/andrecristiani/analise-de-sentimentos-eleicoes-2018/blob/master/SepararPoliticos%20-%20Segundo%20turno/listHaddad.csv

Ordem de execução:

- pre_processamento_anotados
- juncao_bases_2_turno
- pre_processamento_bert
- analise_de_sentimentos_bert


O processamento das análises de sentimentos e de tópicos são executados mais rapidamente caso seja utilizado uma gpu com suporte a CUDA e ele esteja ativado.

O código de Cristiani et al. (2020) utilizando a base pré-processada com enelvo está no diretório codigo_cristiani_et_al_enelvo.


