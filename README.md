# Projeto para o curso de Sistemas Distribuídos


###### O PROJETO

Será desenvolvido um jogo de trocadilhos reunindo vários jogadores. O jogo será separado em rodadas e cada rodada consiste em, dado algum tema sorteado ou palavra sugerido pelo jogo ou pelos próprios jogadores, um tempo será dado para cada pessoa escrever um trocadilho relacionado com aquele tema. Ao fim de cada rodada, todos os trocadilhos são exibidos e todos os jogadores avaliam. O trocadilho com mais votos vence a rodada e o jogador acumula uma pontuação. Ao fim de alguams rodadas, quem tiver a maior pontuação é o vencedor.
###### CLIENT

O Client será um jogador que manda e recebe requisições (novo trocadilho, situação do jogo em tempo real, etc.) ao servidor.
No jogo, até 8 jogadores (clients) poderão se conectar ao server ao mesmo tempo. 

###### SERVER

O Server será o ambiente onde o backend será controlado e os clients poderão interagir.


###### TESTE DE CONCORRÊNCIA

É de extrema importância a verificação de que vários clients conseguem se conectar ao mesmo tempo no server, sem que haja comportamentos inesperados.

###### TESTE DE RECUPERAÇÃO DE FALHAS

Também é importante testar se, caso a comunicação entre um client e o server falhe, não venha a impactar o jogo como um todo.
