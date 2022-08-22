1) Uma simulação sem interação com o usuário não tem muita graça para um jogo, por isso, vamos agora começar a inserir uma interatividade maior.

a.	Inicie seu jogo perguntando para o usuário quantos tanques ele quer criar (entre dois ou dez). Para cada tanque a ser criado, solicite ao jogador o nome do tanque.
b.	Crie a quantidade de tanques solicitada, utilizando agora um dicionário para armazenar cada objeto criado. A chave do dicionário deve ser uma letra, de forma a identificar unicamente cada tanque. Por exemplo:
tanks = {"a":Tank("Alice"), "b":Tank("John"), "c":Tank("Charlie")}
c.	Implemente o Jogo:
i.	A quantidade de tanques representa também a quantidade de jogadores. 

ii.	Para que os últimos jogadores tenham alguma chance de sobreviver, utilize um dado para sortear a vez de cada jogador em cada rodada. O jogador sorteado pode escolher em qual adversário realizará o tiro. Cada jogador terá direito a realizar um tiro a cada rodada.

iii.	Ao final de cada rodada, imprima as informações de cada jogador na tela (quantidade de munição, nível da armadura, etc.).
