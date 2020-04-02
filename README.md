# Exercicio Programa 1 DesSoft
'''
Dupla de programadores aprendizes: Guilherme Ricchetti Carvalho e Lucas Gabriel Mocellin Teixeira.

**Sobre o programa implementado:**
O programa "Jogo_de_Craps" é uma simulação de um jogo de dados muito popular em Cassinos. No entanto, para o jogo virtual, as regras são simplificadas e não cobrem todas as possibilidades de um jogo real. Em suma, foram implementadas duas fases (Come Out e Point). Na fase Come Out, o jogador pode escolher 4 apostas: Pass Line Bet, Field, Any Craps e Twelve; e na fase Point, além da continuação da aposta de Pass Line Bet (caso ele não ganhe nem perca), pode escolher 3 apostas: Field, Any Craps e Twelve. O jogador começa com 100 fichas, escolhe quantas quer apostar em cada aposta, e se acabarem as fichas, o jogo termina.

**Regras detalhadas:**
O jogo se baseia em rodadas sucessivas, nas quais o jogador deve decidir apostar ou sair do jogo, ou automaticamente sair se acabaram as fichas dele. Neste jogo, uma rodada pode ter duas fases, começando com uma chamada de “Come Out” e conforme o resultado, passar para a fase de “Point”. O jogador pode fazer vários tipos de apostas conforme a fase. O jogador sempre é informado em que fase ele está. O computador é quem realiza o lançamento de dois dados (6 lados) para o jogo. Conforme a fase do jogo, o jogador escolhe as apostas e o valor que deseja apostar, ele pode fazer apostas de mais de um tipo por vez. 

Os tipo de apostas são mostradas a seguir:

Pass Line Bet – Esta aposta só pode ser feita na fase de “Come Out”. Se a soma dos dados lançados for 7 ou 11 o jogador ganha (por exemplo: se apostou 10 fichas, mantem as 10 e recebe mais 10). Já se os dados somarem 2, 3 ou 12 (chamado de craps) o jogador perde (ou seja, se apostou 10 fichas, não recebe nada e perde essas 10). Já se a soma dos dados der 4, 5, 6, 8, 9 ou 10 o jogo muda para a fase de “Point” e o objetivo muda. A aposta já feita continua valendo, porém, o valor tirado se torna o Point e para o jogador ganhar agora, a soma do novo lançamento dos dados deve ser igual ao do Point. Se a nova soma dos dados é a mesma do que foi guardado no Point, o jogador ganha o mesmo valor que apostou. Se sair uma soma de valor 7 o jogador perde tudo. Caso saia qualquer outro número, se mantem na fase de “Point” sem perder ou ganhar e se continua lançando os dados até um veredito, quando sair ou o número do Point ou o 7, terminando essa rodada e deixando começar uma nova em “Come Out”.

Field – Esta aposta pode ser feita em qualquer fase do jogo. Nesta aposta se os dados derem 5, 6, 7 ou 8 o jogador perde tudo, já se derem 3, 4, 9, 10, ou 11 o jogador ganha o mesmo valor que apostou, já se a soma for 2 o jogador ganha o dobro do que apostou (se apostou 10 fichas, fica com as 10 e ganha mais 20), e finalmente se sai 12 nos dados o jogador ganha o triplo (se apostou 10 fichas, fica com as 10 e ganha mais 30).

Any Craps – Esta aposta pode ser feita em qualquer fase do jogo. Nesta aposta se o dados derem 2, 3 ou 12 o jogador ganha sete vezes o que apostou, senão perde a aposta.

Twelve – Esta aposta pode ser feita em qualquer fase do jogo. Nesta aposta se o dados derem 12 o jogador ganha trinta vezes o que apostou, senão perde a aposta.

'''
