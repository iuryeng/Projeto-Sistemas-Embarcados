
### Controle de Temperatura usando PID e microcontrolador ATmega328p

####Introdução
> O controle da temperatura feito de maneira adequada é indispensável para uma melhor eficiência em diversos tipos de processos industriais como por exemplo a produção de medicamentos, cultivo de plantas em estufas, fabricação de cerveja, etc. 
A idéia essencial de um dispositivo controlador de temperatura é medir e ajustar a temperatura através da experimentação e correção [1].  Uma solução viável para este tipo de problema é o uso de sistemas embarcados. 
Os sistemas embarcados têm se tornado cada vez mais utilizados como controladores de temperatura além de serem capazes de oferecer maior eficiência, baixo consumo energético e uma maior acessibilidade econômica [2]. Esses sistemas possuem dispositivos de processamento e atuadores capazes de controlar processos e medir  parâmetros que podem  interferir na eficiência de aquecimento [3].  Dessa forma, é possível processar dados de leitura da temperatura a partir de um sensor,  compará-la com uma valor de referência e atuar no ajuste necessário. 

#### Técnica P.I.D 
A técnica de controle PID (Proporcional, Integral e Derivativo) é uma das técnicas de controle mais utilizadas e pode ser implementada via lógica computacional em um sistema embarcado. O controle PID consiste em estabilizar um valor específico a partir de uma variável de interesse ou ponto de referência. A partir desse tipo de controle é possível responder a um tipo de variação da temperatura por meio de uma correção significativa associada ao erro [4] calculado entre a interação sistema/meio físico e o valor de referência ou set point.

### Propósito 

O propósito  deste projeto é modelar matematicamente um controle PID  e implementá-lo em um  protótipo embarcado utilizando o microcontrolador Atmega328p capaz de  controlar a temperatura de um aquecedor.


#### Etapas de Desenvolvimento
Este projeto foi desenvolvido seguindo as seguintes etapas:

* [x] revisão bibliográfica sobre controle PID
* [x] construção de fluxograma de algorítmo PID  
* [x] implementação de PID na liguagem C++
* [x] criação de firmeware contendo o algorítimo em .HEX
* [x] criação de circuito de controle PID no Proteus
* [x] confecção de circuitos no Proteus para simulação
* [x] criação de esquemas de circuito no Eagle
* [x] criação de placa de hardware no Eagle
* [x] produção de vídeo demonstrativo contendo a simulação do projeto 
* [x] produção de vídeo explicativo sobre a implementação do algorítimo de PID
* [x] confecção da documentação do projeto

#### Requisitos para rodar o projeto




