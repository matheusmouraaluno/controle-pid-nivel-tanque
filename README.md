# Título do projeto
Controle de nível de reservatrio de agua com PID utilizando Arduino
# Descrição
O projeto consiste em um desenvolvimento e implementação de uma malha de controle PID (Proporcional, Integral, Derivativo) para regular automaticamente o nível de líquido em um tanque, que utiliza um micro-controlador proporcional integral derivativo (PID), que faz com que o sinal de erro seja minimizado pela ação proporcional, zerado pela ação integral e obtido com uma velocidade antecipativa pela ação derivativa. O controle de nível é realizado através do acionamento de uma válvula na tubulação de entrada, modulando a vazão de alimentação. O circuito funciona em ciclos, em que o reservatório superior encontra-se sempre aberto e possui um sensor ultrasônico de distância para realizar a medição de seu nível. A partir dessa medição do nível, existirá um valor set point no qual o sistema deverá permanecer equilibrado, para que isso ocorra, no reservatório localizado na parte inferior utilizamos uma bomba d'água que faz com que a água retorne para o reservatório superior. 
# Pré-requisitos
Para realizar o projeto é necessário que o programador faça a instalação da IDE do arduíno no site www.arduino.cc para realizar a programação e faça a instalação do software livre de código abertog, para executar a simulação do circuito.
# Lista de Materiais
- Arduíno uno R3
- Mini bomba d'água
- Sensor Ultrasonic HC-SR04
- Estrutura
- Ponte H
- Dois protótipos de reservatorios de água.
