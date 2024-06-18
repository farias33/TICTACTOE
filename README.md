# Jogo da Velha

Este código implementa um jogo da velha simples em C++. Os jogadores se revezam para inserir suas marcas no tabuleiro até que um deles vença ou ocorra um empate. A seguir, um resumo das funcionalidades principais:

## Funcionalidades

### Funções Principais

- `menuInicial()`: Exibe o menu principal do jogo, permitindo que o usuário inicie uma partida, veja informações sobre o jogo ou saia.
- `limpaTela()`: Limpa a tela do console (usando o comando `system("CLS")`).
- `iniciaTabuleiro(char tabuleiro[3][3])`: Inicializa o tabuleiro preenchendo todas as posições com o símbolo '-'.
- `exibeTabuleiro(char tabuleiro[3][3])`: Exibe o tabuleiro no console.
- `confereTabuleiro(char tabuleiro[3][3])`: Verifica se há um vencedor ou se o jogo continua.
- `exibeInstrucoes()`: Mostra as instruções de como jogar, mapeando as posições do tabuleiro.
- `jogo(string nomeDoJogadorUm, string nomeDoJogadorDois, int pontuacaoJogadorUm, int pontuacaoJogadorDois)`: Gerencia a lógica principal do jogo, alternando os turnos dos jogadores e verificando o estado do jogo após cada jogada.

### Como Jogar

1. No menu inicial, escolha a opção para iniciar o jogo e insira os nomes dos dois jogadores.
2. Durante o jogo, insira a posição onde deseja colocar sua marca (X ou O), de acordo com o mapa de posições exibido.
3. O jogo verifica automaticamente se há um vencedor após cada jogada.
4. Após o término de uma partida, é possível escolher entre continuar jogando, voltar ao menu inicial ou sair do jogo.

### Estrutura do Código

- O tabuleiro é representado por uma matriz 3x3 de caracteres.
- As jogadas são inseridas pelos jogadores por meio de entradas no console.
- A função `confereTabuleiro` verifica se há um vencedor ao checar todas as linhas, colunas e diagonais.
- O jogo continua até que todas as posições do tabuleiro sejam preenchidas ou que um jogador vença.

### Exemplo de Uso

Para iniciar o jogo, compile e execute o código. Siga as instruções no console para jogar uma partida de jogo da velha. Após cada partida, você pode escolher continuar jogando, voltar ao menu inicial ou sair.

Divirta-se jogando!
