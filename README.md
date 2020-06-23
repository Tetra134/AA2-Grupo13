# Aprendizagem Automática II - Trabalho prático
# Covid-19 nas regiões de Espanha e Itália

## Grupo 13
- João Aloísio - A77953
- João de Macedo - A76268
- Nelson Gonçalves - A78173

## Introdução

O mundo está a lutar contra um novo inimigo nos dias de hoje, que é o vírus Covid-19.
O vírus espalhou-se rapidamente no mundo desde sua primeira aparição na China. Itália e Espanha foram dos países europeus que mais afetados foram pelo corona vírus.
Este trabalho prático tem como objetivo fazer uma exploração dos dados sobre como o Covid-19 afetou os países Espanha e Itália, focando nas suas regiões. Serão usados os dados sobre o impacto que o vírus teve nestes países até aos dias de hoje.
Posteriormente serão usados modelos deeplearning de maneira a serem obtidas previsões do total de casos infetados por cada região de cada país, bem como o número de curados.

## Exploração dos dados e modelos utilizados

A realização do mesmo foi dividido pelas seguintes fases:

- Carregamento dos dados na pasta [Dados](https://github.com/Tetra134/AA2-Grupo13/tree/master/Data)
	- [Itália](https://github.com/Tetra134/AA2-Grupo13/blob/master/Data/dpc-covid19-ita-regioni2.csv)
	- [Espanha](https://github.com/Tetra134/AA2-Grupo13/blob/master/Data/serie_historica_acumulados.csv)
- Preparação dos dados
- Exploração dos dados em [espanhaVSitalia.ipynb](https://github.com/Tetra134/AA2-Grupo13/blob/master/espanhaVSitalia.ipynb)

Após o carregamentos dos dados para um dataframe, os dados foram devidamente preparados com o objetivo de fazer uma exploração dos mesmos e conseguir ter a perceção de como o vírus afetou cada uma das regiões, tanto de Espanha como Itália. É possível observar e comparar o número de casos infetados, número de mortes, tanto em escala normal como em escala logarítmica. Também é possível observar a evolução da mortalidade ao longo do tempo, a taxa de mortalidade, o aumento de pessoas que requerem hospitalização, como também as pessoas que estão nos cuidados intensivos.

- Construção do modelo baseline em [baseline.ipynb](https://github.com/Tetra134/AA2-Grupo13/blob/master/baseline.ipynb)
Inicialmente foi criado um modelo básico e simples, o modelo baseline. Este modelo foi criado com o objetivo de, posteriormente com a criação de modelos mais complexos, fazer uma comparação e observar se há uma melhoria nas previsões de modo a saber se o modelos mais complexos conseguem fazer melhores previsões.

- Construção do modelo [LSTM](https://github.com/Tetra134/AA2-Grupo13/blob/master/lstm.ipynb)
- Construção do modelo [GRU](https://github.com/Tetra134/AA2-Grupo13/blob/master/GRU.ipynb)


### Bibliografia

Dados:
- [Itália](https://github.com/pcm-dpc/COVID-19/blob/master/dati-regioni/dpc-covid19-ita-regioni.csv)
- [Espanha](https://www.kaggle.com/python10pm/covid19spain)