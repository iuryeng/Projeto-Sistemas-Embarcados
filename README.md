
### Controle de Temperatura usando PID e microcontrolador ATmega328p

> O controle da temperatura feito de maneira adequada é indispensável para uma melhor eficiência em diversos tipos de processos industriais como por exemplo a produção de medicamentos, cultivo de plantas em estufas, fabricação de cerveja, etc. 
A idéia essencial de um dispositivo controlador de temperatura é medir e ajustar a temperatura através da experimentação e correção.  Uma solução viável para este tipo de problema é o uso de sistemas embarcados. 
Os sistemas embarcados têm se tornado cada vez mais utilizados como controladores de temperatura além de serem capazes de oferecer maior eficiência, baixo consumo energético e uma maior acessibilidade econômica. Esses sistemas possuem dispositivos de processamento e atuadores capazes de controlar processos e medir  parâmetros que podem  interferir na eficiência de aquecimento.  Dessa forma, é possível processar dados de leitura da temperatura a partir de um sensor,  compará-la com uma valor de referência e atuar no ajuste necessário. 

#### Técnica P.I.D 
A técnica de controle PID (Proporcional, Integral e Derivativo) é uma das técnicas de controle mais utilizadas e pode ser implementada via lógica computacional em um sistema embarcado. O controle PID consiste em estabilizar um valor específico a partir de uma variável de interesse ou ponto de referência. A partir desse tipo de controle é possível responder a um tipo de variação da temperatura por meio de uma correção significativa associada ao erro  calculado entre a interação sistema/meio físico e o valor de referência ou set point.

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

Para obter um funcionamento por Simulação

* Arduino IDE versão arduino 1.8.5
* Proteus 8.8 (Caso queira simular o projeto no Proteus)
* Eagle 
* ler o procedimento para simulação

Caso tenha o microcontrolador Atmega328p (opcional)

* placa impressa com o circuito elaborado neste projeto
* arduino IDE versão arduino 1.8.5
* gravador AVR para upload do código no Atmega328p

#### Procedimento para obter uma simulação do projeto PID

1. baixe o firmeware contendo o código em hex
2. abra o proteus e logo em seguida abra o arquivo de simulação
3. clique com o botão direito no módulo do microprocessador e adione o firmware em .hex 
4. clique em play (rodar)

> Resultado esperado: você verá a partir da simulação o controle PID do aquecedor que irá manter uma temperatura constante ao chegar em 50% 



#### Procedimento para obter o funcionamento a partir da placa desenvolvida (opcional)

1. a partir do seu gravador AVR grave o arquivo de codigo fonte 
2. ligue aos terminais da placa o aquecedor

### Link no Youtube explicando o funcionamento do algorítimo e a simulação

1. funcionamento: https://www.youtube.com/watch?v=PiqRUjS0RfQ
2. simulação: https://www.youtube.com/watch?v=eSeXs-vWGRQ






