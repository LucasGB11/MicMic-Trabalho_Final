# Microprocessadores e Microcontroladores - Grupo C - Trabalho Final

## Integrantes
- 759030 - Camila Isabel de Souza Bueno - Icamomila (username GitHub)
- 769170 - Davi Batista Silveira - DaviBSilveira (username GitHub)
- 769184 - José Matheus Queiroz Rodrigues - JoseMatheus2802 (username GitHub)
- 769185 - Lucas Gabriel Bassan de Morais - LucasGB11 (username GitHub)
- 770153 -  Matheus Bolson - matheusbolson (username GitHub)

## Objetivo
Desenvolver um disposivo de automação através do controle de energia elétrica a qual passa em algum equipamento eletrônico, como uma lâmpada. Dessa forma, o equipamento deverá ligar e desligar de maneira remota, ou seja, esse poderá ser controlado via internet.

## Materiais utilizados
- Arduino Uno;
- Ethernet Shield;
- Relé;
- Fios de energia, para conectar o aparelho na energia;
- Lâmpada; 
- Celulares;
- Notebook;
- Cabo Ethernet;
- Plugue de tomada fêmea e macho;
- Extensão de energia;

## Breve descrição do desenvolvimento do projeto
Primeiramente será realizada a montagem das conexões entre os módulos e o Arduino da maneira como está na imagem "Montagem Ethernet.png" nesse mesmo repositório. O código utilizado para conexão e controle desses dispositivos esta salvo no arquivo "código" e ele será desenvolvido em linguagem C voltada para Arduino.

Outrossim, para realizar o controle de ligar e desligar dos dispositivos conectados será adaptado um conector de pinos macho e fêmea no qual irá correr a corrente de energia vinda da tomada e, pelo relé, será controlada a função ligar ou deligar dessa corrente.

Por fim, será desenvolvido um aplicativo simples para controle do dispositivo via internet.

## Observações
- SEMANA 1: A ideia inicial preocupava-se apenas com o controle por meio da conexão bluetooth, logo a sugestão de controle via internet ainda não foi implementada. Por conseguinte serão estudados os materiais necessários e a maneira de integração destes com o projeto inicial no decorrer das próximas semanas. Assim, atualizações serão realizadas posteriormente na descrição do projeto. 
- SEMANA 2: Após pesquisas relacionadas ao controle do arduino via internet, foi descartada a ideia inicial de controle pelo bluetooth. Dessa forma, o "Objetivo", "Materiais utilizados" e a "Breve descrição do desenvolvimento do projeto" foram atualidos para comportarem a alteração do projeto.
- SEMANA 3: A ideia inicial de controle de um dispositivo de maneira remota foi concluido. No entanto, com as dificuldades encontradas de conexão entre o arduino e o app android desenvolvido, fizemos novas alterações no projeto. O acionamento do dispositivo será prioritariamente via uma interface web. Caso no decorrer da semana seja desenvolvida uma solução para o aplicativo, esse será mantido no projeto final.
- SEMANA 4: Todas as propostas para o projeto foram concluidas (desenvolvimento de dispositivo de automação através do controle de energia elétrica por via remota, utilizando um aplicativo android via internet). Assim, com base nesse foi desenvolvido a sessão "Reprodução do projeto".

## Reprodução do Projeto (Passo a passo)
- 1. Em "Montagem Ethernet.png", neste mesmo repositório, está ilustrado o modo que foi feita a montagem das conexões entre os módulos e o arduíno. Essa montagem foi colocada dentro do relé, entretanto, o computador serviu como fonte de alimentação para o arduíno. Esse pequeno detalhe pode ser resolvido utilizando uma fonte de alimenação para arduíno apropriada.
- 2. Com a montagem de hardware feita, é necessário realizar o carregamento do código no Arduino, o qual está presente neste repositório. Nesse código está configurado qual o IP que será utilizado pela rede para que seja realizado uma conexão estável com o celular, do qual realizará o controle de energia.
- 3. Para realizar a conexão via rede, foi conectado um cabo de ethernet crossover, que possibilita fazer a ligação “direta” entre dois dispositivos sem a utilização de roteadores. Além disso, é necessário configurar em “Propriedades de Ethernet” o protocolo IP Versão 4 para que os IP’s sejam no mesmo endereço do qual foi utilizado no código do Arduino.
![image](https://user-images.githubusercontent.com/72847338/228102537-f1202f33-5bc6-431f-b6c9-cc76b12034b9.png)
![image](https://user-images.githubusercontent.com/72847338/228102565-425669d7-c401-4d79-870e-40ca19a953c6.png)
- 4. Após isso, é necessário conectar o PC a uma rede wifi e criar uma “Conexão de Ponte” do qual irá ligar a rede wifi com a Ethernet, possibilitando que os dispositivos conectados a rede wireless se comuniquem com os conectados via cabo.
![image](https://user-images.githubusercontent.com/72847338/228102604-9f2c64d9-ec06-4514-a799-ef3122a0afb4.png)
- 5. Para ocorrer a conexão correta entre celular e arduino, tanto o notebook quanto o celular devem estar conectados em um roteador externo, para que o aplicativo mande o comando ao arduino que recebe e executa uma determinada instrução.
- 6. Utilizando o MIT App Inventor foi desenvolvido uma aplicação android de interface simples para ligar e desligar a energia elétrica do dispositivo, além de mostrar o status (LIGADO ou DESLIGADO) - Tanto a parte de Designer, quanto de Blocks do App Inventor necessárias para reproduzir a aplicação estão contidas nas imagens "App Inventor 1" e "App Inventor 2" contidas nesse mesmo repositório.

## Vídeos de apresentação em sala e funcionamento do projeto
https://drive.google.com/folderview?id=1eDrqhmYjWzcIUeZPk6Kxl7Yy-7Pd3-ej

## Referências
- 1- https://www.robocore.net/tutoriais/modulo-rele-arduino - Módulo Relé Arduino
- 2- https://www.youtube.com/watch?v=IUVoIux3oNo&t=385s - Leitura de Sensor - App inventor Ethernet Shield
- 3- https://www.youtube.com/watch?v=4Vc5Rmuu7kc - AppInventor y Arduino Ethernet
- 4- https://www.youtube.com/watch?v=r15dVlsg2wA - Luminárias controladas por Arduino e Ethernet Shield via App Android
- 5- https://vlab.dc.ufscar.br/examples/arduino_uno/web.txt - Exemplo de controle do arduino via web, fornecido pelo Departamento de Computação (DC) da UFSCar
- 6- https://appinventor.mit.edu/ - Plataforma utilizada para desenvolver o app android
