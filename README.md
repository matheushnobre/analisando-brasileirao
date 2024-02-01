# analisando-brasileirao

Este é o meu 1º projeto de análise de dados envolvendo a biblioteca Pandas do Python.
Para praticar conceitos iniciais do Pandas, resolvi trabalhar com algo que amo: dados de futebol.
Para isso, baixei a base de dados dos resultados de todos os jogos do Brasileirão por pontos corridos realizados até então (2003-2023).

Através da visualização desses dados, consegui obter algumas estastísticas que me chamaram a atenção:

Times que participaram apenas uma vez do campeonato por pontos corridos: América-RN, Grêmio Barueri, Brasiliense, CSA, Grêmio Prudente, Ipatinga, Joinville e Santo André.

Clubes que mais venceram:
1. São Paulo (365)
2. Flamengo (354)
3. Santos (340)
4. Internacional (339)
5. Palmeiras (329)
Os 3 primeiros clubes da lista disputaram todas as edições de pontos corridos até então (Santos jogará a série B em 2024).
Chama a atenção o fato do Palmeiras, mesmo não participando de 2 edições do Brasileirão por pontos corridos, estar a frente de rivais como Fluminense (participou de todas as edições), Athletico-PR, Corinthians, Internacional e Atlético-MG, que participaram de mais edições que o time alviverde.

O Fluminense, além de ser um dos 4 únicos a disputar todas as edições por pontos corridos até então, é o clube com mais derrotas (283). Athletico-PR (282), Santos (261), Botafogo(259) e Atlético MG (253) aparecem na sequência.

Já os clubes com mais empates são São Paulo e Corinthians, ambos com 229, seguidos por Flamengo (221), Santos (217) e Fluminense (213).

Levamdo em consideração o aproveitamento dos clubes, podemos dizer que os mais regulares são São Paulo (53,95%), Palmeiras (53,45%), Flamengo (52,28%), Internacional (52,09%) e Corinthians (51,58%).

Já os piores aproveitamentos são de América-RN (14,91%), Santa Cruz (25,88%), Grêmio Prudente (27,19%), Joinville (27,19%) e CSA (28,07%). Curiosamente, desses 5 clubes, o único que disputou o campeonato por pontos corridos mais de uma vez foi o Santa Cruz (2006 e 2016).

Ainda analisando os dados de aproveitamento, aproveitei para ver a diferença de aproveitamento entre mandantes e visitantes. O melhor mandante é o Grêmio (66,76%), enquanto o melhor visitante é o Palmeiras (41,95%). 

Para se ter uma noção do efeito mandante, com exceção de CSA (40,35%), Brasiliense (39,68%), Santa Cruz (39,47%), Grêmio Prudente (35,09%) e América-RN (15,79%), todos os outros clubes possuem aproveitamento jogando em casa superiores ao aproveitamento do melhor visitante, o Palmeiras, conforme citado anteriormente.

Ainda falando sobre a melhora de aproveitamento ao jogar em casa, é perceptível como alguns clubes sabem aproveitar o fator mandante. 
O Grêmio Barueri, embora tenha disputado apenas uma edição do Brasileirão, possuía apenas 21,05% de aproveitamento de visitante, enquanto o aproveitamento como mandante era de 64,91% tendo uma melhora de incríveis 43,86 pontos percentuais.
O Ipatinga (1 participação), que nunca venceu fora de casa, via seu aproveitamento subir 43,86 pontos percentuais ao jogar em casa, chegando a marca de 53,63% de aproveitamento ao jogar como mandante (8,77% de visitante).
Chama a atenção também a melhora de Paysandu (43,78 pontos percentuais), Guarani (39,49 pontos percentuais).
Porém a melhora mais relevante talvez seja a do Athletico-PR, o qual o aproveitamento cresce em 39,49 pontos percentuais ao jogar em casa. O CAP é um dos times com mais jogos no Brasileirão de pontos corridos, tendo resultados significativos ao jogar na Arena da Baixada.

Resolvi analisar também quais clubes marcam mais gols ao vencer. O Grêmio Barueri, que disputou 38 partidas e venceu 12 no campeonato de 2009, tinha a marca de 2.92 gols/jogo quando vencia, seguido por Grêmio Prudente (2.86 em 7 vitórias) e Paysandu (2.56 em 41 vitórias).
Considerando clubes com mais de 50 vitórias, o Náutico é o que mais marca gols ao vencer (2.41 em 54 vitórias), seguido por Vitória (2.41 em 123 vitórias) e Paraná (2.40 em 83 vitórias).

Já os times que menos marcam gols ao vencer são CSA (1.50 gols/jogo em 8 vitórias), Cuiabá (1.79 em 34 vitórias) e Chapecoense (1.96 em 70 vitórias).

Os clubes que mais sofreram gols por derrota foram Paysandu (2.74 gols/jogo em 62 derrotas), Ipatinga (2.62 em 21 derrotas), Náutico (2.58 em 98 derrotas), Juventude (2.54 em 125 derrotas) e Vasco (2.51 em 234 derrotas).

O clube que menos sofre gols ao perder é o Cuiabá (1.77 gols/jogo em 43 derrotas), seguido por Joinville (1.95 gols em 21 derrotas) e São Caetano (2 em 66 derrotas).

No geral, os clubes com mais gols pró por jogo são: Grêmio Barueri (1,55g/j - 38j), Palmeiras (1,45g/j - 734j), Atlético-MG (1,45g/j - 779j), Cruzeiro (1,44g/j - 704j), Santos (1,44g/j - 818j) e Paysandu (1,44g/j - 134j)

Já os qe mais sofrem gols por jogo são: América-RN (2,11g/j - 38j), Santa Cruz (1,91g/j - 76j), Paysandu (1,83g/j - 134j), Ipatinga (1,76g/j - 38j) e Grêmio Prudente (1,68g/j - 38j)