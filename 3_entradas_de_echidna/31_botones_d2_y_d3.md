## 3.1 Botones D2 y D3. {#3-1-botones-d2-y-d3}

El anterior programa ya es un ejemplo de uso de estos botones digitales que están conectados a los pines digitales 2 y 3 de Arduino.
Ten en cuenta que _sólo_ pueden leer niveles lógicos.

**RETO1**

Al pulsar el botón D2 se enciende los 3 leds del Echidna y al soltarlo se apagan. El programa “tunealo” un poco, quitando el oso como disfraz y añadiendo dos que sean Leds

%accordion%SOLUCION RETO1:%accordion%

Previamente hemos descargado de Internet o realizado por nosotros mismos (otra vez ponemos a prueba tus habilidades en el Paint) dos imágenes de leds y se lo añadimos al disfraz del oso (suponemos que sabes algo de Scratch) :

![](/images/image2.png)![](/images/image34.png)

La solución es fácil:

![](/images/image80.png)

%/accordion%

**RETO2**

Al pulsar D2 tiene que encenderse los leds, y **sólo se apagaran** si se vuelve a pulsar D2. O sea, _utilizar sólo un pulsador para encender y apagar los leds__.

%accordion%SOLUCION RETO2:%accordion%

_UN POCO DE PARÉNTESIS TEÓRICO_

Fíjate en el enunciado del RETO1: “al pulsar el botón D2 se enciende y al soltarlo se apaga” ES UNA MÁQUINA LÓGICA pues el estado de la máquina sólo depende de las entradas (en este caso de un botón): Pulsar la entrada (botón D2) produce una salida concreta (encender leds).

_CONTINUAMOS ..._

Pero tal y como está redactado, el RETO2 tiene que memorizar el estado anterior, no es trivial el enunciado “Al pulsar D2 tiene que encenderse los leds, y sólo se apagaran si se vuelve a pulsar D2.” ES UNA MÁQUINA SECUENCIAL pues el estado de la máquina depende de las entradas y de lo que ha pasado antes. Pulsar la entrada (botón D2) NO produce una salida concreta (depende si estaba apagado o encendido anteriormente).

No pasa nada si no lo entiendes del todo, es teoría.

La programación se complica añadiendo una variable que recuerde lo que ha pasado antes la vamos a llamar encendido que recordará si está encendido los leds o no:

![](/images/image56.png)

¿qué pinta ese “esperar 0.5s? je, je, je…. te vamos a dejar que lo experimentes tú, quitalo, pruébalo varias veces y verás…

Muchos de nuestros aparatos electrónicos se encienden y se apagan con el mismo botón, así que a partir de ahora aprecia que su funcionamiento no es trivial.

%/accordion%