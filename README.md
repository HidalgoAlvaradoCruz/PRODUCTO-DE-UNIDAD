**SIMULACIÓN Y RESOLUCIÓN DE PROBLEMAS IMPLEMENTANDO CIRCUITOS COMBINACIONALES**

**1.PLANTEAMIENTO DEL PROBLEMA**

Se desconoce el funcionamiento, diseño y conexión de un circuito votador, un circuito comparador y un circuito con representación binaria, para lo cual se formularon las siguientes preguntas: 

•	¿Cómo se diseña un circuito votador?

•	¿Cómo se diseña un circuito coparador?

•	¿Cómo se diseña un circuito que tenga como entradas la representación binaria de la hora actual menos ocho?

**2.OBJETIVOS**

**Objetivo general**

Realizar el diseño de diferentes circuitos combinacionales con aplicaciones.

**Objetivos específicos**

•	Diseñar un circuito votador y la influenza en la seguridad de aviones modernos.

•	Diseñar un circuito que tenga como entradas la representación binaria aplicado a un horario laboral de una factoría.

•	Diseñar un circuito comparador exclusivamente con puertas NOR.

**3.ESTADO DEL ARTE**

**4.MARCO TEÓRICO**

**Circuito Combinacional**
Un circuito combinacional es un circuito electrónico, en el que el valor de sus salidas en un determinado instante, dependen del valor de las entradas en ese mismo instante. Es decir, es un circuito que carece de memoria. Trabajan con números, y con la tecnología con la que están realizados, estos números están representados en binario.
El siguiente circuito:

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img1.png)

En un determinado instante van a depender de las entradas en ese preciso instante. Estos circuitos se caracterizan porque no almacenan información. Las salidas están relacionadas con las entradas a través de una función booleana.
Cada bit de salida de un circuito combinacional, se obtiene mediante una función booleana aplicado a las variables de entrada. Así, si un circuito tiene n salidas, necesitaremos n funciones booleanas para caracterizarlo.
Así, un circuito combinacional que tiene 3 entradas:A,B y C, y dos salidas F, G, que son dos funciones booleanas que dependen de las variables de entrada: F(A,B,C) y G(A,B,C), siendo por ejemplo, el valor de las funciones:

F = A + C'D

G = AB' + D

Se obtiene un circuito combinacional como este:

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img2.png)

**Circuito comparador**

Un circuito comparador compara dos entradas binarias (A y B de n bits) para indicar la relación de igualdad o desigualdad entre ellas por medio de "tres banderas lógicas" que corresponden a las relaciones A igual B, A mayor que B y A menor que B. Cada una de estas banderas se activará solo cuando la relación a la que corresponde sea verdadera, es decir, su salida será 1 y las otras dos producirán una salida igual a cero.

**Circuito votador**

Es conocido el uso de redundancia en aplicaciones electrónicas con altos requisitos de seguridad ante fallos. Las técnicas de redundancia implican utilizar una pluralidad de circuitos independientes para obtener un solo resultado. Cada uno de los circuitos genera una señal de salida, por lo que es necesario un sistema votador ("voter" en inglés) , que indica cual es el valor de salida más repetido. Dicho valor más repetido pasa a considerarse el resultado de salida del sistema de redundancia.
**App Inventor**

App Inventor es un entorno de desarrollo de software creado por Google para la elaboración de aplicaciones destinadas al sistema operativo de Android. El lenguaje es gratuito y se puede acceder fácilmente de la web. Las aplicaciones creadas con App Inventor están limitadas por su simplicidad, aunque permiten cubrir un gran número de necesidades básicas en un dispositivo móvil.
Con App Inventor, se espera un incremento importante en el número de aplicaciones para Android debido a dos grandes factores: la simplicidad de uso, que facilitará la aparición de un gran número de nuevas aplicaciones; y Google Play, el centro de distribución de aplicaciones para Android donde cualquier usuario puede distribuir sus creaciones libremente.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img3.png)

**Dislay De 7 Segmentos**

El display de 7 segmentos es un dispositivo electrónico que se utiliza para representar visualmente números y algunos caracteres. Este display es muy popular debido a su gran efectividad y simplicidad al momento de utilizarlo.

**Partes de un display de 7 segmentos**

Se le conoce como 7 segmentos por que cuenta con siete diodos led principales y uno extra para representar un punto. También cuenta con una carcasa para cubrirlos y 10 terminales: 2 son de alimentación (2 de Vcd o 2 de Gnd), 1 es para visualizar un punto y  7 son para representar cada uno de los números según la combinación que se le ponga, estos están representados por una letra del abecedario desde la “A” hasta la letra “G”.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img4.png)

**Funcionamiento de un display**

Para poder representar los números o caracteres con este dispositivo solo basta con saber la configuración de cada una de sus leds y combinarlos.

**5.DESARROLLO Y SIMLACIÓN**

**ENUNCIADO #1**

**Las normas de seguridad de los modernos aviones exigen que, para señales de vital importancia para la seguridad del aparato, los circuitos deben estar triplicados para que el fallo de uno de ellos no produzca una catástrofe. En caso de que los tres circuitos no produzcan la misma salida, ésta se escogerá mediante votación. Diseñe el circuito "votador" que ha de utilizarse para obtener como resultado el valor mayoritario de las tres entradas.**

Análisis:

El proceso de votación consiste en tomar el valor mayoritario de las entradas.
De esta forma, la salida, f, del circuito tendrá la siguiente codificación :

– f = 0 si hay más ceros que unos en las entradas

– f = 1 si hay más unos que ceros en las entradas

El circuito votador tiene tres señales de entrada : a,b y c, que son las salidas de los circuitos triplicados .

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img5.jpg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img6.jpg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img7.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img8.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img9.jpg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img10.jpeg)

Simulación y Diagramas

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img11.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img12.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img13.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img14.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img15.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img16.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img17.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img18.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img19.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img20.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img21.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img22.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img23.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img24.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img25.png)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img27.png)

**ENUNCIADO #2**

**El horario laboral de una factoría es de 8 horas diarias, divididas en tres turnos: de 8 a 11 (primer turno), de 11 a 13 (segundo turno), de 13 a 16 (descanso) y de 16 a 19 (tercer turno). Se pretende diseñar un circuito que tenga como entradas la representación binaria de la hora actual menos ocho y que proporcione a la salida el número de turno que está trabajando (si procede) o "0" si es hora de descanso.
Diseñe un módulo adicional que permita visualizar en un display de 7 segmentos el número del turno que corresponda.**

Anális:

Para implementar este circuito consideramos que cada turno se desarrolla en un lapso de tiempo específico considerando la hora laboral como: 8 a 9, 9 a 10, 10 a 11, ……………18 a 19 quedando un total de 11 horas posibles.
En un primer análisis la HORA ACTUAL son números decimales del 8 al 18 que al momento de cumplir la condición impuesta por el enunciado (HORA ACTUAL – 8), queda un intervalo del 0 al 10, finalmente las ENTRADAS que se van a utilizar para el desarrollo del problema es la representación en binario del último intervalo ( 0 al 10).

Ejemplo: 

Hora actual: 8 		Hora actual – 8:    8 – 8 = 0	Representación binaria: 0 0 0 0

Hora actual: 9 		Hora actual – 8:    9 – 8 = 1	Representación binaria: 0 0 0 1

 Así sucesivamente hasta completar el intervalo, para la representación binaria del 10 se necesita una entrada de 4 bits
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img29.jpeg)

 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img30.jpeg)
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img31.jpeg)
 
 Simulación y Diagramas
 
**ENUNCIADO #3**

**6.LISTA DE COMPONENTES ENFOCADO EN EL ENUNCIADO DOS**

**7.MAPA DE VARIABLES ENFOCADO EN EL ENUNCIADO DOS**

**6.EXPLICACIÓN DEL CÓDIGO FUENTE ENFOCADO EN EL ENUNCIADO DOS**

**9.DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN**

**10.APORTACIONES**

**11.CONCLUSIONES**

En conclusión:

•	El circuito diseñado utilizado como norma de seguridad de aviones modernos tiene tres señales de entrada que son las salidas triplicadas así si un circuito llegara a fallar quedarían dos en buen estado, evitándose una catástrofe.



**12.RECOMENDACIONES**

Es de vital importancia conocer el funcionamiento de un circuito votador y las puertas lógicas básicas que se podrían utilizar.

**13.CRONOGRAMA**

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img28.jpeg)

**14.BIBLIOGRAFÍA**

**15.ANEXOS**

**15.1.MANUAL DE USUARIO ENFOCADO EN EL E UNUNCIADO TRES**

**15.2.HOJAS TÉCNICAS**

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img32.png)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img33.png)
