 __O projeto de prevenção contra incêndio foi realizado no TinkerCad , uma plataforma com suporte para programação em arduino, neste documento haverá em detalhes o processo passo a passo para a realização deste sistema:__

Na primeira etapa do projeto foram coletados dados de quais materiais viriam a ser utilizados para assim ser colocado uma Protoboard da qual atendesse o tamanho do projeto. Inicialmente foi proposto um projeto “simples” com apenas 1 sensor e 1 led, mas ao decorrer das discussões sobre este sistema foram impostas ampliações das quais foram necessárias  o uso de uma placa de ensaio maior, assim mudando completamente a estrutura básica do projeto.
 	
	
Inicialmente só foi previsto o uso de um sensor como dito acima, que no caso seria o sensor de temperatura que atuaria juntamente com um led piscante indicando quando há risco de incêndio, assim que esta parte foi finalizada no esquema e nos códigos, era perceptível que aquele sistema era muito simples, por conta disso foi decidido ampliações para ele, tendo como objetivo tornar este projeto bom, para que futuramente fossem inscrito em competições, como o hackaduino.


A primeira ampliação prevista foi o uso de um sensor de som, inicialmente parecia uma ideia muito promissora, mas ao decorrer do projeto este componente começou a dar interferência no sistema como um todo, assim tendo que excluí-lo temporariamente (Quando este projeto for levado para competições, construindo-o em ambiente real, será imposto o sistema de som novamente, pois depois de diversos testes, foi descoberto que o problema estava na plataforma e não no código do sistema).


A segunda ampliação proposta foi o uso de mais dois sensores, que seria usados para validar ainda mais as informações sobre um possível incêndio, contendo assim três verificações agora. Os dois sensores adicionados foram o de fumaça (utilizado o sensor de gás pelo Tinkercad) e também o sensor de umidade que serve para medir a umidade do solo assim tendo informações de quando o solo está seco(podendo aumentar o risco do incêndio se propagar no local).
A terceira ampliação foi adicionar mais 3 LEDs no projeto, assim como um botão que seria utilizado para ligar e desligar o sistema. Os LEDs foram utilizados da seguinte forma:1 é utilizada como aviso para saber se o sistema está ligado ou desligado, as demais leds são utilizadas para informar quando há risco de incêndio, sendo uma para cada sensor(Vale lembrar que se os 3 sensores forem ativados, as 3 LEDs piscam de modo intermitente e aciona o LCD contendo a informação de “RISCO DE INCÊNDIO: CRITICO!!”).


Mesmo adicionando todos esses componentes, ainda faltava uma interface para o projeto, com isso em mente, foi adicionado um sensor infravermelho, um controle remoto e também uma tela LCD. O sensor infravermelho serve para captar os sinais recebidos pelo controle remoto, tais sinais servem para controlar as informações que são exibidas na tela LCD, permitindo o operador do sistema mostrar diversas informações, como a temperatura de um local, a porcentagem de umidade e também se há presença de fumaça.
	O processo de montagem do projeto foi dado ao decorrer das ampliações assim como mostrado a cima, juntamente com a programação em Arduino de cada um dos componentes.
   
