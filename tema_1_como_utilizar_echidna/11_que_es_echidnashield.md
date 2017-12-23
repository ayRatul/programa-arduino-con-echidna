## 1.1 ¿Qué es EchidnaShield?

### 1.1.1 Primero ¿qué es Arduino? ¿qué es una Shield? {#1-1-1-primero-qu-es-arduino-qu-es-una-shield}

**¿Qué es Arduino?** Pues no podemos explicarlo en este curso, suponemos que lo conoces,  te recomendamos que [visites nuestro curso Arduino con código y Edubasica en esta página](https://catedu.gitbooks.io/programa-arduino-mediante-codigo/content/index0.html), si la lees verás que tiene un inconveniente: Arduino es una placa microcontroladora orientado para las entradas y las salidas tanto analógicas como digitales, pero…. **tienes que ponerlas**, y eso implica cableado y electrónica.

Una solución es utilizar una Shield, está adaptado para ponerlo encima e incluso hay posibilidad utilizar varias a la vez.

![](/assets/image14.png)

[Enrique Crespo](https://aprendiendoarduino.wordpress.com) CC-BY-SA

Hay muchas en el mercado:

* Para las comunicaciones:
  * [EthernetShield](http://arduino.cc/en/Main/ArduinoEthernetShield).
  * [WifiShield](http://arduino.cc/en/Main/ArduinoWiFiShield)
  * [GSMShield móvil GPRS](http://arduino.cc/en/Main/ArduinoGSMShield)
* Para salidas concretas
  * [Motores](http://arduino.cc/en/Main/ArduinoMotorShieldR3)
  * [Relés RelayShield](http://wordpress.redirectingat.com)
* Para entradas concretas
  * [OpenEnergy Medidor Medidor de magnitudes eléctricas](http://openenergymonitor.org/emon/emontxshield)
* Para facilitar la conexión de sensores y actuadores
  * [Grove Shield](http://wordpress.redirectingat.com) donde hay una familia sensores y actuadores de conectar y listo asociados.

Hay tantos que la lista es interminable…

Y otras están orientadas para el uso educativo:

* [Edubásica ](http://www.practicasconarduino.com/edubasica/)que en Aularagón tenemos [un curso dedicado](https://catedu.gitbooks.io/programa-arduino-mediante-codigo/content/una_placa_de_apoyo_edubsica.html) a esta Shield creada por docentes y para docentes.
* ¿Y cómo no?: nuestra estrella en este curso [Echinda](http://echidna.es/)

Hay muchas más Shields …. prueba poner las palabras_ Shield Arduino_ en tu buscador.

También hay que nombrar “_entrenadores_” educativos para Arduino, “Kits de principiantes”, etc.. los hay con muchos sensores y otros muy compactos como [Evive](https://www.hackster.io/evive/products/evive): en el [vídeo](https://www.youtube.com/watch?time_continue%3D35%26v%3D3F0_JspobN0&sa=D&ust=1513946282798000&usg=AFQjCNGSPO-_LZPb4pH3iPYWYPi3_JXU1g) explican muy bien las ventajas de utilizar una Shield/entrenador frente a usar la electrónica pura.

### 1.1.2 Ahora sí: ¿Qué es Echidna? {#1-1-2-ahora-s-qu-es-echidna}

Es una Shield de Arduino diseñada para facilitar la programación del Arduino en los últimos cursos de primaria y primeros de secundaria, pensado en minimizar el cableado de la electrónica \(ya lo sabemos pues es una Shield\) y enfocado a nivel educativo y al lenguaje por símbolos

_¿Por qué hemos elegido esta Shield?_

Por varias razones:

* Es OpenHardware, por lo tanto es un proyecto con garantías de estabilidad, libre, colaborativo y vivo, con la misma filosofía que la placa Arduino.
* Salidas acertadas:
* Diodos Red D13, Orange D12 y Green D11.
* Diodo de 3 colores RGB gobernados por D9, D5 y D6 respectivamente.
* Audio en D10.
* Entradas o sensores acertados:
* Joystick \(estupendo para hacer proyectos atractivos\) xy con A0 y A1
* Acelerómetro \(idem\) xy en A2 y A3
* Luz LDR en A5
* Botones digitales D2 y D3
* Conexión Bluetooth que da más potencial a nuestros proyectos.
* Es MakeyMakey: Dos Shields en una: Sensores y [MakeyMakey](https://www.makeymakey.com) por lo tanto da más potencial a nuestros proyectos.\(Tenemos [un curso en Aularagon de MakeyMakey\)](http://moodle.catedu.es)
* Es barato y asequible para la mayoría de los centros.
* Tiene pines para conexión de otros elementos como relés pero no pueden pasar de 300mA para más potencia es mejor utilizar Shield adaptados para ello como Edubásica.



