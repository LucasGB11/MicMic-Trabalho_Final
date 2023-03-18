# Microprocessadores e Microcontroladores - Grupo C - Trabalho Final

## Integrantes
- 759030 - Camila Isabel de Souza Bueno
- 769170 - Davi Batista Silveira 
- 769184 - José Matheus Queiroz Rodrigues
- 769185 - Lucas Gabriel Bassan de Morais 
- 770153 -  Matheus Bolson

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

## Referências
- https://www.robocore.net/tutoriais/modulo-rele-arduino - Módulo Relé Arduino
- https://www.youtube.com/watch?v=IUVoIux3oNo&t=385s - Leitura de Sensor - App inventor Ethernet Shield
- https://www.youtube.com/watch?v=4Vc5Rmuu7kc - AppInventor y Arduino Ethernet
- https://www.youtube.com/watch?v=r15dVlsg2wA - Luminárias controladas por Arduino e Ethernet Shield via App Android
- https://vlab.dc.ufscar.br/examples/arduino_uno/web.txt - Exemplo de controle do arduino via web, fornecido pelo Departamento de Computação (DC) da UFSCar
