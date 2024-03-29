**Jogo de Memória com Arduino**

Este projeto implementa um jogo de memória simples usando um Arduino. O jogo consiste em mostrar uma sequência de LEDs piscando em uma ordem específica, que o jogador precisa repetir pressionando os botões correspondentes.

Link do projeto no TinkerCad https://www.tinkercad.com/things/bEBh60mMptV-jogo-da-memoria-com-leds?sharecode=8tFFMYSzsOso707T8irfwYWFkkednaemF4nk5vCQG1M

![image](https://github.com/MiguelAngelo88/Genius-com-Arduino/assets/104993355/ac4de5ab-4fbd-49b0-b718-fe3c18dcf769)



**Materiais Necessários**

• Arduino Uno (ou similar)

• 4 LEDs

• 4 Resistores de 220 Ω

• 4 pushbuttons

• Cabos jumpers


**Montagem do Circuito**

Conecte os LEDs aos pinos 4, 5, 6 e 7 do Arduino, e os botões aos pinos 8, 9, 10 e 11. Certifique-se de usar resistores para limitar a corrente dos LEDs e configurar os botões com resistores pull-up.

![image](https://github.com/MiguelAngelo88/Genius-com-Arduino/assets/104993355/a7369d16-520e-4286-98d7-16f227939162)


**Funcionamento**

1. Quando o jogo é iniciado, uma sequência de LEDs é gerada aleatoriamente e mostrada ao jogador.
2. O jogador deve repetir a sequência pressionando os botões na ordem correta.
3. Se o jogador acertar, a sequência é aumentada em um LED e o LED verde irá piscar 3 vezes para sinalizar o acerto.
4. Se o jogador errar, a sequência é reiniciada e o LED vermelho irá piscar 3 vezes para sinalizar o erro.
5. O jogador pode reiniciar o jogo a qualquer momento pressionando o botão de Reset do Arduino.
6. O jogador tem até 10 segundos para apertar algum botão, caso contrário o jogo é reiniciado.
7. O jogo continua até que o jogador erre a sequência.
