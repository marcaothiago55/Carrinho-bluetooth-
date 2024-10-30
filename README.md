HC-06 só funciona em android e o app versão 1.0.6 baixado pelo Google versões antigas 

# Descrição Detalhada do Projeto: Controle de Robô com Gamepad

Este projeto exemplar, concebido pelo Professor Thiago Antonio Marcão e desenvolvido para a aula 29 de Robótica Paraná na Escola Otalipío, apresenta uma aplicação empolgante e educativa que combina eletrônica, programação e interatividade. Por meio desse projeto, os alunos têm a oportunidade de se envolver ativamente com a tecnologia enquanto aprendem sobre o funcionamento de sistemas robóticos, comunicação serial, controle de hardware e muito mais.

Objetivo:
O objetivo central deste projeto é permitir que os alunos controlem um robô remotamente usando um gamepad. O robô, equipado com motores e LEDs, pode realizar movimentos específicos e exibir feedback visual em resposta aos comandos do gamepad. Além disso, o projeto visa cultivar a compreensão prática dos princípios de eletrônica e programação, incentivando os alunos a aplicar seus conhecimentos teóricos em um ambiente real.

Componentes-Chave:

Microcontrolador (por exemplo, Arduino): O cérebro do sistema, responsável por interpretar os comandos do gamepad e controlar os dispositivos conectados.
Módulo de Gamepad: Um componente essencial que permite aos alunos enviar comandos de controle ao robô, resultando em movimentos e ações específicas.
Motores: Essenciais para conferir movimento ao robô. O projeto utiliza quatro motores (INT1, INT2, INT3 e INT4) para possibilitar movimentos em todas as direções.
LEDs: Usados para fornecer feedback visual instantâneo. Os LEDs nos pinos LED_PIN_12 e LED_PIN_13 estão ligados diretamente aos movimentos do robô.
Biblioteca Dabble: Uma ferramenta vital para a comunicação serial entre o microcontrolador e o gamepad, permitindo a interação e o controle eficaz.
Fluxo de Funcionamento:
O projeto inicia com a configuração inicial no método setup(), onde a comunicação serial é estabelecida e os pinos são definidos de acordo com os componentes usados. O sistema, então, entra em um loop contínuo (loop()) no qual ele processa as entradas do gamepad usando a função Dabble.processInput(). Dependendo dos comandos recebidos (para cima, para baixo, esquerda, direita), as funções correspondentes são ativadas, acionando os motores apropriados para criar movimento no robô. Quando nenhum comando é recebido, a função stopCar() é chamada para interromper os motores e definir os LEDs para indicar um estado de parada.

Impacto Educacional:
Esse projeto oferece uma experiência educacional enriquecedora, pois combina teoria e prática de maneira tangível. Além de aprender sobre eletrônica, programação e controle de dispositivos, os alunos também desenvolvem habilidades de solução de problemas, pensamento crítico e colaboração. A interação direta com o hardware e a obtenção de feedback visual e auditivo reforçam a compreensão dos conceitos.

Materiais Necessários:

2 Motores DC 3-6 V para mover o nosso carrinho;
Chassi e duas rodas (você pode optar também por imprimir seu próprio chassi e até mesmo rodas em 3D!);
Arduino Uno R3 Compatível;
Uma Shield Ponte H L298 n;
Módulo bluetooth Rs232 Hc05;
Chave Liga-Desliga 10A;
Suporte 4 Pilhas AA;
Ferro de solda;
Estanho;
Jumpers;
4 pilhas médias;
