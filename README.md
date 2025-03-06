# JogoPY

- **Nome**: Gabriel da Silva Oliveira Costa
- **RA**: 124113980
- **Professor**: Alexandre Montanha

## Descrição do Jogo

O **JogoPY** é um jogo interativo onde o objetivo é adivinhar um número secreto de 1 a 100. Você pode escolher entre adivinhar um número **par**, **ímpar**, ou **qualquer número** dentro desse intervalo. O jogo oferece um desafio, pois você terá um número limitado de tentativas para adivinhar o número correto.

## Regras do Jogo

1. **Escolha do tipo de número**:
   - Você pode escolher entre:
     - **Par**: O número secreto será sempre par.
     - **Ímpar**: O número secreto será sempre ímpar.
     - **Ambos**: O número secreto pode ser qualquer número dentro do intervalo.

2. **Número de tentativas**:
   - Você pode escolher o número de tentativas, com um máximo de **20 tentativas** para adivinhar o número secreto.

3. **Pontuação**:
   - Sua pontuação começa com **100 pontos**.
   - Cada tentativa errada reduz sua pontuação, e a perda de pontos depende da proximidade do seu palpite em relação ao número secreto:
     - Quanto mais próximo você estiver do número, menos pontos você perde.
     - Quanto mais distante você estiver, mais pontos serão descontados.

4. **Feedback sobre a proximidade**:
   - Durante o jogo, o sistema indica se você está muito longe ou perto do número secreto. As tentativas mais próximas terão um destaque especial no gráfico, mostrando o quão perto você chegou.

5. **Final do jogo**:
   - Se você acertar o número secreto, o jogo terminará com uma mensagem de vitória e a pontuação final.
   - Se você atingir o limite de tentativas sem acertar, o jogo termina e revela o número secreto.
   - No final, é exibido um gráfico mostrando a evolução das suas tentativas, além de mostrar as últimas 3 tentativas e o quanto você se aproximou do número secreto.

6. **Reiniciar o jogo**:
   - Ao final do jogo, você terá a opção de jogar novamente, mantendo a mesma lógica e desafios.

## Requisitos

- Python 3.x
- Biblioteca `matplotlib` para visualização gráfica. Instale com:
  ```bash
  
  pip install matplotlib

**Como Jogar**:
* 1- Copie o codigo e cole no (https://colab.google/).
* 2- Abra um New Notebook
* 3- Clique em + codigo e cole o codigo do jogo. 
* 4- Divirta-se 

