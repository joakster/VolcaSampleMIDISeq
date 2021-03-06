# VolcaSampleMIDISeq
Secuenciador MIDI para volcasample

Dentro de la carpeta de "Volca" se encuentra una versión inestable del secuenciador con la capacidad de hacer diferentes patrones rítmicos, desde negras hasta cinquillos en cada tiempo de la secuencia.

La carpeta de "16Step_V1" contiene una versión donde solamente está secuenciando 16 notas (4 semicorcheas), por lo tanto es una versión mucho más fácil de utilizar, aparte de que es muy estable al momento de correr.

# Versión 16Step_V1

![Screen Shot 2022-03-27 at 19 40 03](https://user-images.githubusercontent.com/10868602/160312351-4363e2be-afbc-47bb-80e9-6df055263572.png)

Del lado izquierdo en la parte de arriba se encuentra el botón de inicio y el tiempo marcado como BPM (Beats por minuto), del lado derecho aparecen unos botones que se encienden al momento de correr la secuencia y de esta manera saber en qué parte va.

Abajo de estos botones se ven los diferentes sonidos que tiene el volca sample, al activarlos en un lugar determinado harán que suenen en el tiempo indicado.

Cada sonido está mapaeado al canal MIDI correspondiente (del canal 1 al 10).

# Versión Volca

Esta versión funciona de una manera similar a la anterior, pero tiene la diferencia en que podemos escoger diferentes figuras rítmicas para cada tiempo.

![Screen Shot 2022-03-28 at 12 30 14](https://user-images.githubusercontent.com/10868602/160463587-ed845334-6cb4-43ff-91a6-aa09e7b8c678.png)

De igual forma seleccionamos qué partes de la secuencia queremos que suene.

![Screen Shot 2022-03-28 at 12 30 22](https://user-images.githubusercontent.com/10868602/160463713-f47415d6-71d6-4e01-a757-002e930da27e.png)

Para asignar las figuras en cada tiempo solamente tenemos que poner el número para cada una, el 1 es una negra, el 2 son corcheas, el 3 tresillos, así hasta cinquillos.

Ahora bien, es importante mencionar que si seleccionamos por ejemplo el número 2, solamente van a escucharse las primeras dos casillas en ese tiempo y el programa ignorará las siguientes 3.
