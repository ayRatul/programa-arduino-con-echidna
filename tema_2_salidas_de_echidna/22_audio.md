## 2.2 Audio {#2-2-audio}

RETO

Vamos a retomar el programa de los tonos, el programa lo puedes descargar de este [repositorio](https://www.google.com/url?q=https://drive.google.com/drive/folders/1pXcRUqMM7q_UK0QhILd9QwLe8KtPCM5m?usp%3Dsharing&sa=D&ust=1513946282847000&usg=AFQjCNHZMNrtgAiR1B5_-RYaSKYpcsL1zQ):

![](images/image23.png)

Si lo ejecutamos desde el ordenador, y pulsamos el botón D2 se oye un tut, tut, tut por los auriculares, ya dijimos en [este apartado](../tema_1_como_utilizar_echidna/12_como_se_programa_echidna_shield.md#1-2-4-7-subir-a-arduino) que la culpa lo tiene tu ordenador: No es capaz de enviar mBlock órdenes al Arduino a la velocidad de 0.00175 segundos. Si pulsamos el botón D3 se oye el tono C4 sin problemas.

La solución consiste en subir al arduino ¿cómo se hace? mira esta [presentación](https://www.google.com/url?q=https://docs.google.com/presentation/d/e/2PACX-1vTkh8pwo-b7LACnD7_ZAfWzYCchZI9H1_uR-tZqgfBRtOPFOaVDH8ognsCNEXA8khLI7UX6ziUQXZsx/pub?start%3Dfalse%26loop%3Dfalse%26delayms%3D3000&sa=D&ust=1513946282848000&usg=AFQjCNF-RkZZDtHb-eWpB2fP4vGzbfAAmg):

&lt;iframe src=&quot;https://docs.google.com/presentation/d/e/2PACX-1vTkh8pwo-b7LACnD7_ZAfWzYCchZI9H1_uR-tZqgfBRtOPFOaVDH8ognsCNEXA8khLI7UX6ziUQXZsx/embed?start=false&amp;loop=false&amp;delayms=3000&quot; frameborder=&quot;0&quot; width=&quot;960&quot; height=&quot;569&quot; allowfullscreen=&quot;true&quot; mozallowfullscreen=&quot;true&quot; webkitallowfullscreen=&quot;true&quot;&gt;&lt;/iframe&gt;

El resultado es [este vídeo](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DWbA8p_yC-90&sa=D&ust=1513946282849000&usg=AFQjCNGe1jjBxBeK9oFVVTOeXQxUxxFvNg)

https://www.youtube.com/watch?v=WbA8p_yC-90

### 2.2.1 No es lo mismo {#2-2-1-no-es-lo-mismo}

Si pulsamos D2 el sonido es más agudo que pulsando D3 que corresponde a la nota C4 ¿por qué?

Los cálculos del tiempo de subida y bajada tiempo=0.00175s calculados [anteriormente](../tema_1_como_utilizar_echidna/12_como_se_programa_echidna_shield.md#1-2-4-1-instrucciones-espec-ficas-para-arduino) están bien hechos ¿por qué no reproduce bien el tono de la nota C4? por esto:

![](images/image76.png)

No es lo mismo una onda analógica sinusoidal de 282 Hz que una onda digital cuadrada que es lo que se reproduce en la salida digital D10

¿Y por qué se oye más agudo? Vamos a fijarnos en una transición por ejemplo la de bajada de 5V a 0V ¿A qué se parece más esa transición?

![](images/image15.png)

Evidentemente a la segunda, y esa pendiente tan vertical corresponde más a ondas agudas:

![](images/image48.png)

Por lo tanto se oye más agudo, por eso es

Ya sé que el anterior razonamiento, si lo lee algún físico, le producirá un rechinar de dientes ![](images/image63.png)

pues para los frikis: … la transformada Fourier de una onda cuadrada produce armónicos de orden superior, incluso infinitos si fuese perfecta..., ja!, pero es mejor ser simple que ser incomprensible.