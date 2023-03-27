# Microprocessadores e Microcontroladores - Grupo C - Trabalho Final

## Integrantes
- 759030 - Camila Isabel de Souza Bueno - Icamomila (username GitHub)
- 769170 - Davi Batista Silveira -  (username GitHub)
- 769184 - José Matheus Queiroz Rodrigues -  (username GitHub)
- 769185 - Lucas Gabriel Bassan de Morais - LucasGB11 (username GitHub)
- 770153 -  Matheus Bolson - matheusbolson (username GitHub)

## Objetivo
Desenvolver um disposivo de automação através do controle de energia elétrica a qual passa em algum equipamento eletrônico, como uma lâmpada. Dessa forma, o equipamento deverá ligar e desligar de maneira remota, ou seja, esse poderá ser controlado via internet.

## Materiais utilizados
- Arduino uno;
- Ethernet Shield;
- Relé;
- Fios de energia, para conectar o aparelho na energia;

## Breve descrição do desenvolvimento do projeto
Primeiramente será realizada a montagem das conexões entre os módulos e o Arduino da maneira como está na imagem "Montagem Ethernet.png" nesse mesmo repositório. O código utilizado para conexão e controle desses dispositivos esta salvo no arquivo "código" e ele será desenvolvido em linguagem C voltada para Arduino.

Outrossim, para realizar o controle de ligar e desligar dos dispositivos conectados será adaptado um conector de pinos macho e fêmea no qual irá correr a corrente de energia vinda da tomada e, pelo relé, será controlada a função ligar ou deligar dessa corrente.

Por fim, será desenvolvido um aplicativo simples para controle do dispositivo via internet.

## Observações
- SEMANA 1: A ideia inicial preocupava-se apenas com o controle por meio da conexão bluetooth, logo a sugestão de controle via internet ainda não foi implementada. Por conseguinte serão estudados os materiais necessários e a maneira de integração destes com o projeto inicial no decorrer das próximas semanas. Assim, atualizações serão realizadas posteriormente na descrição do projeto. 
- SEMANA 2: Após pesquisas relacionadas ao controle do arduino via internet, foi descartada a ideia inicial de controle pelo bluetooth. Dessa forma, o "Ojetivo", "Materiais utilizados" e a "Breve descrição do desenvolvimento do projeto" foram atualidos para comportarem a alteração do projeto.
- SEMANA 3: A ideia inicial de controle de um dispositivo de maneira remota foi concluido. No entanto, com as dificuldades encontradas de conexão entre o arduino e o app android desenvolvido, fizemos novas alterações no projeto. O acionamento do dispositivo será prioritariamente via uma interface web. Caso no decorrer da semana seja desenvolvida uma solução para o aplicativo, esse será mantido no projeto final.
- SEMANA 4: Todas as propostas para o projeto foram concluidas (desenvolvimento de dispositivo de automação através do controle de energia elétrica por via remota, utilizando um aplicativo android via internet). Assim, com base nesse foi desenvolvido a sessão "Reprodução do projeto".

## Reprodução do Projeto (Passo a passo)
- 1.
- 2.
- 3.
- X. Utilizando o MIT App Inventor foi desenvolvido uma aplicação android de interface simples para ligar e desligar a energia elétrica do dispositivo, além de mostrar o status (LIGADO ou DESLIGADO) - Tanto a parte de Designer, quanto de Blocks do App Inventor necessárias para reproduzir a aplicação estão contidas nas imagens "App Inventor 1" e "App Inventor 2" contidas nesse mesmo repositório.

## Referências
- 1- https://www.robocore.net/tutoriais/modulo-rele-arduino - Módulo Relé Arduino
- 2- https://www.youtube.com/watch?v=IUVoIux3oNo&t=385s - Leitura de Sensor - App inventor Ethernet Shield
- 3- https://www.youtube.com/watch?v=4Vc5Rmuu7kc - AppInventor y Arduino Ethernet
- 4- https://www.youtube.com/watch?v=r15dVlsg2wA - Luminárias controladas por Arduino e Ethernet Shield via App Android
- 5- https://vlab.dc.ufscar.br/examples/arduino_uno/web.txt - Exemplo de controle do arduino via web, fornecido pelo Departamento de Computação (DC) da UFSCar
- 6- https://appinventor.mit.edu/ - Plataforma utilizada para desenvolver o app android
