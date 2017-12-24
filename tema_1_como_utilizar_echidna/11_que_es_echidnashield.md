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
  * [Motores](https://store.arduino.cc/arduino-motor-shield-rev3)
  * [Relés RelayShield](http://arduino.cl/2-relay-shield/)
* Para entradas concretas
  * [OpenEnergy Medidor Medidor de magnitudes eléctricas](http://arduino.cl/arduino-energy-shield/)
* Para facilitar la conexión de sensores y actuadores
  * [Grove Shield](https://www.seeedstudio.com/Grove-Base-Shield-p-754.html) donde hay una _**familia sensores y actuadores de conectar y listo**_ asociados, veremos en la unidad 5 que Echidna tiene 3 I/O digitales y una analógica para estos sensores, es decir es también una versión pequeña Grove Shield que nos permitirá hacer robots .

Hay tantos que la lista es interminable…

Y otras están orientadas para el uso educativo:

* [Edubásica ](http://www.practicasconarduino.com/edubasica/)que en Aularagón tenemos [un curso dedicado](https://catedu.gitbooks.io/programa-arduino-mediante-codigo/content/una_placa_de_apoyo_edubsica.html) a esta Shield creada por docentes y para docentes.
* ¿Y cómo no?: nuestra estrella en este curso [Echinda](http://echidna.es/)

Hay muchas más Shields …. prueba poner las palabras_ Shield Arduino_ en tu buscador.

También hay que nombrar “_entrenadores_” educativos para Arduino, “Kits de principiantes”, etc.. los hay con muchos sensores y otros muy compactos como [Evive](https://evive.cc/): por cierto explican muy bien las ventajas de utilizar una Shield/entrenador frente a usar la electrónica pura.

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

**¿Estás preparado? adelante !!!**

<iframe src="https://giphy.com/embed/bvBeK27koljaM" width="470" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/big-bang-theory-sheldon-cooper-the-bigbang-bvBeK27koljaM">via GIPHY</a></p>



