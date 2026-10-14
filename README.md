Análise Exploratória sobre Edições de Campeonatos do Mundo
**Descrição do Projeto**
Este projeto apresenta uma Análise Exploratória de Dados (EDA) focada na história dos Campeonatos do Mundo de Futebol da FIFA (de 1930 a 2022). 
Através da linguagem Python, o notebook extrai estatísticas históricas, tendências de golos, assistência de público e o impacto do "fator casa" nas diferentes edições do torneio.  

**Fonte de Dados** 
dados analisados provêm do ficheiro worldcups_atualizado.csv. A base de dados contém as seguintes informações sobre cada torneio: 
year: Ano da edição.
host: País anfitrião.
winner, second, third, fourth: Seleções que ocuparam os quatro primeiros lugares.
goals_scored: Total de golos marcados.
teams: Número de seleções participantes.
games: Número total de jogos disputados.
attendance: Assistência total (público).  

Bibliotecas Utilizadas
pandas - Para manipulação, limpeza e análise da base de dados.  
matplotlib.pyplot - Para a criação das visualizações e gráficos.   
numpy - Para suporte em operações numéricas.  

**Análises e Visualizações**
O projeto desenvolve as seguintes análises:  

Maiores Campeões do Mundo: Identificação e visualização em gráfico de barras horizontais das seleções com mais títulos.  
Seleções com mais Vices: Contagem e representação gráfica dos países que mais vezes perderam finais.  
Média de Golos por Edição: Análise temporal da média de golos marcados por jogo, identificando tendências históricas, a edição com maior média e a edição com menor média.  
Média de Público por Edição: Visualização da evolução da assistência média por partida ao longo dos anos, destacando os recordes e os valores mínimos.  
Desempenho do País-Sede: Uma análise sobre quão longe o país anfitrião chega na competição (Campeão, Vice, 3º lugar, 4º lugar ou fora do pódio).  

**Principais Conclusões**  
Liderança Histórica: O Brasil é o maior campeão com 5 títulos, seguido de perto por Itália e Alemanha com 4.  
Quase Lá: A Alemanha também lidera no número de vice-campeonatos (4 vezes), seguida por Argentina e Países Baixos (Holanda) com 3.  
Evolução Tática (Golos): As médias de golos eram muito mais altas antes da década de 2000. O recorde absoluto foi em 1954 (5,38 golos por jogo), em contraste com o valor mínimo alcançado em 1990 (2,21 golos). Esta quebra reflete o aumento do rigor tático e do foco defensivo ao longo do tempo.  
Recorde de Assistência: O Mundial de 1994, nos Estados Unidos, mantém a maior média de público por jogo. A menor média ocorreu em Itália, no ano de 1934.  
O Fator Casa: Jogar em casa representa uma grande vantagem. Em 6 edições, o país anfitrião conseguiu sagrar-se campeão do torneio.  

**Como executar**  
Certifique-se de que possui o Python instalado no seu ambiente.
Instale as bibliotecas necessárias caso não as possua (pip install pandas matplotlib numpy).  
Garanta que o ficheiro worldcups_atualizado.csv se encontra no diretório especificado no notebook (/content/worldcups_atualizado.csv ou ajuste o caminho de acordo com o seu ambiente).   Execute as células do notebook para reproduzir os gráficos e resultados.














