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

En 2009, Zhaohui Gan, Gang Shi y Tao Shang de la Facultad de Ciencias de la Información e Ingeniería, Universidad de Ciencia y Tecnología de Wuhan realizaron un estudio implementando circuitos lógicos combinacionales en el diseño automático de la programación genética (GP). GP usando una estructura de árbol o una estructura lineal en lugar de cadenas para representar un circuito lógico combinacional. En el método GP, los nodos hoja y los nodos padres representan señales de entrada y puertas lógicas en circuitos, respectivamente. Los circuitos también evolucionan con algoritmos de selección clonal basado en gráficos (Zhaohui Gan, 2009, p.1) [1].
Alidoust Zahra y Basiri Mohammad, del Departamento de ingeniería informática Departamento de Ingeniería Universidad de Isfahan y de la Universidad Shahrekord, Irán en 2017 centraron su estudio en mejorar el algoritmo genético a través de la agrupación para el diseño de circuitos lógicos combinacionales, los diseños evolutivos son buenas alternativas para el diseño de circuitos lógicos pero tienen un inconveniente común, a saber, la alta aleatoriedad de su método cruzado. Para superar este inconveniente el método propuesto, se adopta el algoritmo k-means para optimizar el algoritmo genético con el fin de aumentar la eficiencia y reducir el costo de producción. Los criterios de optimización de los elementos del circuito, como el recuento de puertas de los transistores y el consumo de energía (Zahra Alidousti,2017, p.1) [2].

Mukherjee, B. y Dandapat, Dept, Jadavpur University Kolkata, en el Simposio internacional 2010 presentaron un estudio sobre el diseño de sistemas electrónicos mediante el método combinacional cíclico para VLSI de baja potencia. El objetivo principal del circuito cíclico es introducir retroalimentación estructural y evitar la retroalimentación lógica para obtener una salida primaria combinatoria. El estudio del circuito cíclico incluye análisis funcional, es decir, para determinar qué valores aparecerán, el análisis de tiempo que determina cuándo aparecerán estos valores y el área. El objetivo del estudio es diseñar y verificar diferentes circuitos combinacionales en un método cíclico mediante la optimización del área, la potencia y el retraso.
 (L Mukherjee, B. y Dandapat, 2010, p.1) [3]. 
 
Youjun Xu, Dantong Ouyang1, Yuxin Ye, y Jialiang He, Facultad de Informática y Tecnología Jilin University, Changchun, China, en su trabajo de investigación basado en la solución de problemas SAT con álgebra booleana expusieron que en las últimas décadas, se proponen muchos métodos de SAT, basado en la resolución, por medio de la regla de extensión, en el estudio de la regla de extensión, encontramos que el problema SAT se puede resolver con algoritmos de configuración de golpe. Si podemos encontrar un conjunto de aciertos de un conjunto de cláusulas, y si no hay ningún par de literales complementarios en el conjunto de aciertos, el conjunto de cláusulas es satisfactoria. El algoritmo BHS basado en el álgebra booleana propuesto por Jiang es un algoritmo de conjunto de golpes eficiente.  (Xu, Y., Ouyang, D., Ye, 2010, p.1) [4]. 

Ruanqianqian Huang y Franklyn Turbak del Wellesley College, Department of Computer Science en 2019 implementaron un diseño para la conversión bidireccional entre bloques y texto para App Inventor mediante fragmentos de código visual que evitan errores semánticos sintácticos y estáticos y reducen la carga cognitiva para este fin diseñaron un sistema de modo dual para MIT App Inventor que admite representaciones textuales para bloques, espacios de trabajo, pantallas y proyectos completos que permiten la conversión bidireccional entre bloques isomorfos y representaciones de texto, permitiendo que individuos de varios niveles de experiencia en programación se relacionen con la interfaz (R. Huang,F. Turbak,2019)[5].

Para el Producto de Unidad presente, se utilizó una estructura de árbol o una estructura lineal en lugar de cadenas para representar un circuito lógico combinacional (Zhaohui Gan, 2009, p.1), para la optimización de los elementos del circuito, como el recuento de puertas de los transistores y el consumo de energía se utilizó parte de los postulados empleados en algoritmo genético con circuitos combinacionles (Zahra Alidousti,2017, p.1)  el entorno de programación para el aplicativo se hizo sobre la base de MIT App Inventor, el sistema tiene la capacidad de proyectar un número decimal de salida  en la pantalla del dispositivo android simulando la proyección de un display de 7 segmentos (R. Huang,F. Turbak,2019).

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
 
 Primer turno 
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img58.png)
 
 Segundo turno  
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img59.png)
 
 Descanso 
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img60.png)
 
 Tercer turno 
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img61.png)
 
 Primer turno 
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img62.png)
 
 Segundo turno 
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img63.png)
 
 Descanso 
 
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img64.png)
 
  Tercer turno 
  
 ![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img65.jpeg)
 
**ENUNCIADO #3**

**Se pretende diseñar un circuito comparador de 2 números de 2 bits, A = (a1, a0) y B = (b1, b0 ). Dicho circuito deberá tener tres salidas M, l, m, de tal forma que:
 M = 1 si A>B 
L= 1 si A=B 
m = 1 si A < B 
Diseñe exclusivamente con puertas NOR.** 

Análisis:

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img34.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img35.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img36.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img37.jpeg)


Simulación y Diagramas


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img38.jpeg)

Cumple la condición de M=1 ; si A˃B

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img39.jpeg)

Cumple la condición de m=1 ; si A<B 

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img40.jpeg)

Cumple la condición de L=1 ; si A=B 

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img41.jpeg)

**7.MAPA DE VARIABLES ENFOCADO EN EL ENUNCIADO DOS**
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img56.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img57.jpeg)

**6.EXPLICACIÓN DEL CÓDIGO FUENTE ENFOCADO EN EL ENUNCIADO DOS**
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img51.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img52.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img53.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img54.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img55.jpeg)

**9.DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN**

Tener una cuenta de Google activa es esencial, debido a que la verificación y creación de la cuenta en APP INVENTOR y TINKERCAD será a partir de esta. 

Es esencial tener una conexión estable a internet, debido que será necesario para la creación del programa en app inventor. 

Los sistemas operativos de los computadores en los cuales funciona app inventor son: 

•	Macintosh (con procesador Intel): Mac OS X 10.5, 10.6

•	Windows: Windows XP, Windows Vista, Windows 7

•	GNU / Linux: Ubuntu 8 +, 5 + Debian


Tener un computador con todas las actualizaciones necesarias, como también nuestro navegador deberá tener las siguientes especificaciones: 

•	Mozilla Firefox 3.6 o superior

•	Apple Safari 5.0 o superior

•	Google Chrome 4.0 o superior

La aplicación creada con App Inventor puede funcionar en cualquier teléfono Android. El entorno de desarrollo y software de instalación se apoya directamente a los teléfonos siguientes: Los dispositivos adicionales requieren los controladores de Windows proporcionados por el fabricante del hardware.

Para realizar los test de nuestro programa en el móvil, será necesario descargarnos una app desde play store para Android. El nombre de la app es “MIT AI2 Companion”

**10.APORTACIONES**

Implementación en físico del circuito votador.

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img42.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img43.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img44.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img45.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img46.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img47.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img48.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img49.jpeg)
**11.CONCLUSIONES**

En conclusión:

•	El circuito diseñado utilizado como norma de seguridad de aviones modernos tiene tres señales de entrada que son las salidas triplicadas así si un circuito llegara a fallar quedarían dos en buen estado, evitándose una catástrofe.

•	 Dado un problema que conlleva realizar una o varias acciones se lo puede resolver fragmentándolo en una o varias funciones lógicas implementadas en un circuito combinacional, estas funciones por lo general son expresiones extensas según el problema o el número de entradas o salidas que se necesite, a estas expresiones se las pueden simplificar en una expresión más trabajada por medio de aplicar los teoremas del Álgebra Booleana o los Mapas de Karnaugth , siendo este último el más óptimo para simplificar expresiones extensas, basado en la resolución del ejercicio número 2 se puede llegar a una función simplificada solo aplicando los teoremas del Álgebra Boleana 


**12.RECOMENDACIONES**

•	Es de vital importancia conocer el funcionamiento de un circuito votador y las puertas lógicas básicas que se podrían utilizar.

•	Al momento de plantear las variables del problema no generar variables innecesarias ya que lo único que se va a conseguir con ello es generar una función más extensa de lo realmente necesario, una vez establecida la tabla el método más recomendable para hallar la función es fijarse en la cantidad de “0” y “1” que tiene la o las salidas de esta forma se puede implementar min-términos si la cantidad de “1” es menor y máx-términos si la cantidad de “0” es menor, esto facilitará en gran medida los cálculos posteriores.

**13.CRONOGRAMA**

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img28.jpeg)

**14.BIBLIOGRAFÍA**

[1] Gan, Z., Shi, G. y Shang, T. (2009). La síntesis automática de circuitos lógicos combinacionales con algoritmo de selección clonal basado en gráficos. 2009 Conferencia Internacional sobre Inteligencia Artificial e Inteligencia Computacional. doi: 10.1109 / aici.2009.267 

[2] Alidousti, Z. y Basiri, ME (2017). CGACLC: Mejora del algoritmo genético a través de la agrupación para el diseño de circuitos lógicos combinacionales. 2017 Tercera Conferencia Internacional sobre Reconocimiento de Patrones y Análisis de Imágenes (IPRIA). doi: 10.1109 / pria.2017.7983062 

[3] Mukherjee, B. y Dandapat, AK (2010). Diseño de circuitos combinacionales mediante el método combinacional cíclico para VLSI de baja potencia. Simposio internacional 2010 sobre diseño de sistemas electrónicos. doi: 10.1109 / ised.2010.29 

[4] Xu, Y., Ouyang, D., Ye, Y. y He, J. (2010). Solución de problemas SAT con álgebra booleana. Quinta Conferencia Internacional 2010 sobre la frontera de la informática y la tecnología. doi: 10.1109 / fcst.2010.13 

[5] Huang, R. y Turbak, F. (2019). Un diseño para la conversión bidireccional entre bloques y texto para App Inventor. 2019 IEEE Blocks and Beyond Workshop (B&B). doi: 10.1109 / bb48857.2019.8941197 

[6] Gonzales,Erick,(2018). Display 7 Segmentos ánodo y cátodo común.Recuperado de:
https://hetpro-store.com/TUTORIALES/display-7-segmentos-anodo-catodo-comun/

[7]Posada.Fernando,(2019). Creando aplicaciones para móviles Android con MIT App Inventor 2. DOI (web) 104438/2695-4176_OTE_2019_847-19-121-5. https://intef.es/wp-content/uploads/2019/03/MIT-App-Inventor-2.pdf

**15.ANEXOS**

**15.1.MANUAL DE USUARIO ENFOCADO EN EL E UNUNCIADO DOS*

1.	Para ejecutar la aplicación Turnos_Factoria, primero se debe instalar el apk MIT AI2 Companion en nuestro Smartphone con sistema ANDROID 6.0 en adelante, la descarga del apk  se la realiza directamente del Play Store o en el enlace:	  https://play.google.com/store/apps/details?id=edu.mit.appinventor.aicompanion3&hl=es


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/86.jpg)

2.	Desde un ordenador dirigirse al sitio web de App Inventor seleccionamos el proyecto Turnos_factoria en el enlace: http://ai2.appinventor.mit.edu/?locale=es_ES#4887093323366400

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/87.jpg)

3.	Se puede visualizar la interfaz gráfica del proyecto, dar clic sobre la pestaña Conectar / Al Companion 

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/88.jpg)

4.	Aparece un código QR como paso siguiente se debe abrir la aplicación MIT App Inventor 2 en el celular y escanear  dicho código dando clic en la opción “scan QR code” y esperamos que se vincule nuestro dispositivo con el sitio web.


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/89.jpg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/90.jpg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/91.jpg)

5.	Automáticamente la aplicación se abre en el celular, en el campo “ingrese el código respectivo para realizar una consulta” se puede ingresar “0” o “1”


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/92.jpg)

6.	Una vez ingresado el valor deseado le damos clic en CONSULTAR TURNO, se puede observar que la aplicación nuestra tanto la HORA ACTUAL como la (HORA ACTUAL – 8)


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/93.jpg)

7.	Finalmente, para ingresar un nuevo número, se debe dar clic en el botón “NUEVO TURNO” caso contrario dar clic en la opción “SALIR” para cerrar la aplicación. 

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/94.jpg)

**15.2.HOJAS TÉCNICAS**

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img32.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img33.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img66.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img67.jpeg)

![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img68.jpeg)
![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img69.jpeg)


![](https://github.com/HidalgoAlvaradoCruz/PRODUCTO-DE-UNIDAD/blob/master/img/img33.png)


