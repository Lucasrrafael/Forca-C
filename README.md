# Jogo da Forca em C

Este é um jogo de Forca desenvolvido em C. O código permite que o jogador adivinhe uma palavra secreta, fornecendo sugestões de letras. O jogo termina quando o jogador acerta a palavra ou esgota o número de tentativas permitidas.

Funcionalidades principais:

Leitura de palavras: A palavra secreta é escolhida aleatoriamente de um arquivo de texto (palavras.txt), com a opção de adicionar novas palavras ao banco de dados.
Lógica do jogo: O jogador tenta adivinhar letras, com feedback sobre se a letra existe ou não na palavra secreta.
Desenho da forca: O jogo desenha uma representação da forca à medida que o jogador comete erros.
Condições de vitória/perda: O jogo verifica se o jogador venceu (adivinhou todas as letras da palavra) ou perdeu (tentativas esgotadas).
Adição de palavras: O jogador pode adicionar novas palavras ao banco de dados de palavras, aumentando a variedade de desafios no jogo.
Requisitos:

Um compilador C que suporte o padrão ISO C99 ou C11 para evitar erros relacionados à declaração de variáveis no cabeçalho de loops for.
Arquivo palavras.txt com palavras para o jogo.

## Pré-requisitos

- GCC (ou compilador C de sua escolha)
- Sistema operacional Linux, macOS ou Windows

## Como compilar o código

1. Abra o terminal e navegue até o diretório onde o arquivo `forca.c` está localizado.
2. Execute o seguinte comando para compilar o código:

   - **No Linux/macOS**:

     ```sh
     gcc -o forca forca.c
     ```

   - **No Windows com MinGW**:

     ```sh
     gcc -o forca.exe forca.c
     ```
## Como rodar o programa

Após a compilação, execute o programa:

- **No Linux/macOS/Windows**:

  ```sh
  ./forca
  ```

  
