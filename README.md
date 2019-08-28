# Projeto para o curso de Sistemas Distribuídos


###### O PROJETO

Será desenvolvido um jogo de perguntas e respostas reunindo vários jogadores. O jogo será separado em rodadas e cada rodada consiste em, dado algum tema sorteado ou escolhido por algum dos jogadores, será feita alguma pergunta de conhecimentos gerais sobre aquele tema e todos os jogadores devem responder corretamente o mais rápido possível. A pontuação de cada rodada será dada pela resposta certa no menor tempo, ou seja, quanto menor o tempo da resposta correta, mais pontuação será recebida. Ao final de X rodadas ou uma determinada pontuação, o vencedor será escolhido.

###### CLIENT

O Client será um jogador que manda e recebe requisições (respostas da pergunta, situação do jogo em tempo real, etc.) ao servidor.
No jogo, até 8 jogadores (clients) poderão se conectar ao server ao mesmo tempo. 

###### SERVER

O Server será o ambiente onde o backend será controlado e os clients poderão interagir.


###### TESTE DE CONCORRÊNCIA

É de extrema importância a verificação de que vários clients conseguem se conectar ao mesmo tempo no server, sem que haja comportamentos inesperados.

###### TESTE DE RECUPERAÇÃO DE FALHAS

Também é importante testar se, caso a comunicação entre um client e o server falhe, não venha a impactar o jogo como um todo.
