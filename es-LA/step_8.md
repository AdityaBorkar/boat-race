## Obstáculos e impulsores

En este punto, el juego parece **muy** fácil, por eso, necesita agregar más elementos para hacerlo lucir más interesante.

Primero, debe añadir algunos impulsores para aumentar la velocidad del bote.

\--- task \---

Edite el fondo del Escenario agregando algunas flechas blancas impulsoras.

![captura de pantalla](images/boat-boost.png)

\--- /task \---

\--- task \---

Ahora agrega mas código de bloques al ciclo`infinito` de tu objeto bote para que se realice tres pasos extras cuando toque una flecha blanca. ![objeto-bote](images/boat_resize.png)

```blocks3
si <touching color [#FFFFFF] ?> luego
mover (3) pasos
fin
```

\--- /task \---

\--- task \---

Pruebe su juego para determinar si la nueva flecha impulsora aumenta la velocidad de su bote.

\--- /task \---

Luego, añada un portal giratorio que el bote deberá evitar.

\--- task \---

Añada un nuevo portal que se vea igual y nómbrelo "portal":

![captura de pantalla](images/boat-gate.png)

Asegurese de que el color del portal sea el mismo que el de las vallas de madera.

\--- /task \---

\--- task \---

Asegurese de que el centro del portal se encuentre ubicado en el centro.

![captura de pantalla](images/boat-center.png)

\--- /task \---

\--- task \---

Añada el código al portal para crear una rotación lenta infinita.

\--- hints \--- \--- hint \--- Añada el bloqueo del código al portal para que `gire 1 grado` `infinitamente`. \--- /hint \--- \--- hint \--- Los bloqueos de código que necesitará se encuentran a continuación: ![portal](images/gate.png)

```blocks3
siempre
fin

gire (1) grado en onda contínua

cuando seleccione el indicador
```

\--- /hint \--- \--- hint \--- Así debería lucir su nuevo código: ![portal](images/gate.png)

```blocks3
cuando seleccione el indicador
siempre
gire (1) grado en onda continua
fin
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Pruebe su juego nuevamente. En este momento, debería haber un portal giratorio y usted deberá mover el bote al rededor del mismo.

![captura de pantalla](images/boat-gate-test.png)

\--- /task \---