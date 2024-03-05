**Jogo de Memória com Arduino**

Este projeto implementa um jogo de memória simples usando um Arduino. O jogo consiste em mostrar uma sequência de LEDs piscando em uma ordem específica, que o jogador precisa repetir pressionando os botões correspondentes.

**Materiais Necessários**

• Arduino Uno (ou similar)
• 4 LEDs
• 4 Resistores de 220 Ω
• 4 pushbuttons
• Cabos jumpers

**Montagem do Circuito**

Conecte os LEDs aos pinos 4, 5, 6 e 7 do Arduino, e os botões aos pinos 8, 9, 10 e 11. Certifique-se de usar resistores para limitar a corrente dos LEDs e configurar os botões com resistores pull-up.

**Funcionamento**

1. Quando o jogo é iniciado, uma sequência de LEDs é gerada aleatoriamente e mostrada ao jogador.
2. O jogador deve repetir a sequência pressionando os botões na ordem correta.
3. Se o jogador acertar, a sequência é aumentada em um LED e o LED verde irá piscar 3 vezes para sinalizar o acerto.
4. Se o jogador errar, a sequência é reiniciada e o LED vermelho irá piscar 3 vezes para sinalizar o erro.
5. O jogo continua até que o jogador erre a sequência.
