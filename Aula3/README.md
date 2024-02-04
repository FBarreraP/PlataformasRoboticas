<h1>Aula 3</h1>

Esta clase se basa en entender el funcionamiento del driver de potencia para variar la velocidad y el giro de un motor DC.

<h2>Puente H</h2>

El puente H para motores DC es un arreglo de cuatro transistores NPN, PNP y/o MOSFET que tienen como objetivo, conmutar el sentido de la corriente sobre el motor DC. Algunos drivers de potencia comerciales y de bajo costo son el L293 y L298, los cuales están conformados por transistores NPN que trabajan en dos estados: a) corte (interruptor abierto) o b) saturación (interruptor cerrado). Los transistores NPN cuando tienen un voltaje positivo en la base funcionan como interruptor cerrado y cuando tienen un voltaje de 0V en la base funcionan como interruptor abierto. En el caso de los transistores PNP el funcionamiento con respecto a los voltajes es inverso a los transistores NPN.

<img src="https://www.inventable.eu/wp-content/uploads/2017/05/motor_dc_sentido_de_giro.png" alt="giros motor DC" caption="Hola"/>

Fuente: https://www.inventable.eu/2017/05/26/funciona-puente-motores-corriente-continua/

<img src="https://www.inventable.eu/wp-content/uploads/2017/05/motor_dc_puente_con_interruptores0.png" alt="puente H" caption="Hola"/>

Fuente: https://www.inventable.eu/2017/05/26/funciona-puente-motores-corriente-continua/

![Giros puente H](image.png)

Fuente: https://www.inventable.eu/2017/05/26/funciona-puente-motores-corriente-continua/

<h2>PWM</h2>

PWM es una modulación por ancho de pulso de una señal cuadrada, donde se define un tiempo en alto (Duty Cycle) y un tiempo en bajo. Es utilizado para variar la velocidad de motores DC, la intensidad de leds, etc.

<img src="https://i0.wp.com/descubrearduino.com/wp-content/uploads/2020/04/Técnica-PWM.jpg?w=583&ssl=1" alt="PWM" caption="Hola"/>

Fuente: https://descubrearduino.com/l293d/

<h2>L298</h2>

El puente H L298 está conformado por transistores NPN y el cual tiene un salida de 2A por cada canal. 

<img src="https://www.luisllamas.es/wp-content/uploads/2016/05/arduino-l298n-conexion.webp" alt="L298 pinout" caption="Hola"/>

Fuente: https://www.luisllamas.es/arduino-motor-corriente-continua-l298n/

<img src="https://www.luisllamas.es/wp-content/uploads/2016/05/arduino-l298n-esquema.webp" alt="L298 conexiones eléctricas" caption="Hola"/>

Fuente: https://www.luisllamas.es/arduino-motor-corriente-continua-l298n/

Teniendo en cuenta valores de resistencias de precisión (RSA y RSB) muy bajos (ej: 0.05 Ohm) y midiendo los voltajes en los puntos SENS A y SENS B con respecto a tierra, se puede calular la corriente que consume cada motor a través de la Ley de Ohm (I=V/R).

<img src="https://www.inventable.eu/wp-content/uploads/2017/05/L298_internal.png" alt="L298 transistores NPN" caption="Hola"/>

Fuente: https://www.inventable.eu/2017/05/26/funciona-puente-motores-corriente-continua/

<img src="https://www.prometec.net/wp-content/uploads/2016/11/L298N-dos-motores-DC.png" alt="L298 con Arduino" caption="Hola"/>

Fuente: https://www.prometec.net/l298n/



<img src="" alt="" caption="Hola"/>
<img src="" alt="" caption="Hola"/>


<img src="" alt="" caption="Hola"/>