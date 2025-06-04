# IsItReal

En esta experiencia de realidad mixta en **gravedad 0** tienes un único propósito: contar cuantas teteras hay en la habitación. Para ello, deberás seleccionar una de las cartas con el número que te proponen, ¿podrás cumplir con el objetivo?

### Cómo jugar

> **AVISO:** Al hacer uso de *herramientas experimentales*, puede que la aplicación se cierre al iniciar la experiencia o al volver a escanear la sala (actualizarla). Si esto sucede, vuelve a abrir la aplicación sin actualizar la habitación desde la misma, puedes hacerlo desde la configuración de las gafas.
Si aparece el mensaje "Could not load MR Scene Model.", puede que Unreal falle en cargar la escena.

Los controles son sencillos: se puede interactuar con los objetos con únicamente tu mano izquierda (para más dificultad), lo que te permite coger los objetos virtuales con el dedo índice y el pulgar (pinch).

Deberás contar el número de teteras reales, por lo que te recomiendo cogerlas para probar su veracidad.

![image](Video/pinch.png)

Cuando sepas la respuesta a la pregunta que se te propone, deberás escoger la carta con la respuesta y dejarla sobre la mesa. ¡TEN CUIDADO! Algunos objetos no se consideran REALES, deberás averiguar si lo son.

### Licencias
Todos los modelos 3D han sido desarrollados por mí. Si se quieren hacer uso de ellos, contactad conmigo.

Otros assets como el SkyLight se ha escogido de Unreal.

#### Sonido
##### background_sound.wav 
* <a href="https://freesound.org/people/Dwy/sounds/581829/">Tape No. R-S 5 (Lo-fi loop)</a> by <a href="https://freesound.org/people/Dwy/">Dwy</a> | License: <a href="http://creativecommons.org/publicdomain/zero/1.0/">Creative Commons 0</a><br>
* <a href="https://freesound.org/people/felineterror/sounds/581642/">R-S 5</a> by <a href="https://freesound.org/people/felineterror/">felineterror</a> | License: <a href="http://creativecommons.org/publicdomain/zero/1.0/">Creative Commons 0</a>

##### 571502__kagateni__cute1.mp3
* <a href="https://freesound.org/people/Kagateni/sounds/571502/">Cute1.mp3</a> by <a href="https://freesound.org/people/Kagateni/">Kagateni</a> | License: <a href="https://creativecommons.org/licenses/by/4.0/">Attribution 4.0</a>

##### 658270__lilmati__retro-spare-or-eat-cute-creature.mp3

* <a href="https://freesound.org/people/LilMati/sounds/658270/">Retro, Spare Or Eat Cute Creature.wav</a> by <a href="https://freesound.org/people/LilMati/">LilMati</a> | License: <a href="http://creativecommons.org/publicdomain/zero/1.0/">Creative Commons 0</a>

#### 546081__stavsounds__correct3.wav

* <a href="https://freesound.org/people/StavSounds/sounds/546081/">correct3.wav</a> by <a href="https://freesound.org/people/StavSounds/">StavSounds</a> | License: <a href="http://creativecommons.org/publicdomain/zero/1.0/">Creative Commons 0</a>

#### 351563__bertrof__game-sound-incorrect-with-delay.wav

* <a href="https://freesound.org/people/Bertrof/sounds/351563/">Game Sound Incorrect With Delay</a> by <a href="https://freesound.org/people/Bertrof/">Bertrof</a> | License: <a href="http://creativecommons.org/licenses/by/3.0/">Attribution 3.0</a>

#### 588234__mehraniiii__win.wav

* <a href="https://freesound.org/people/mehraniiii/sounds/588234/">win.wav</a> by <a href="https://freesound.org/people/mehraniiii/">mehraniiii</a> | License: <a href="http://creativecommons.org/publicdomain/zero/1.0/">Creative Commons 0</a>

#### 362206__taranp__horn_fail_wahwah_1.wav

* <a href="https://freesound.org/people/TaranP/sounds/362206/">horn_fail_wahwah_1.wav</a> by <a href="https://freesound.org/people/TaranP/">TaranP</a> | License: <a href="http://creativecommons.org/publicdomain/zero/1.0/">Creative Commons 0</a>

## Entrevista

### Proceso de creación

P: **¿Qué dificultades has encontrado durante el desarrollo? ¿Cómo las has resuelto?**

La principal dificultad del desarrollo de esta experiencia ha sido el trabajar con herramientas experimentales. La realidad mixta de Meta va evolucionando y actualizandose constantemente en el momento de la creación de este proyecto, impidiendo que sea un proceso suave.
Para resolver estos problemas, he optado por quedarme con una versión específica del plugin MRUK e intentar adaptarlo a las necesidades de las gafas.

Un problema que no he logrado aplacar ha sido el de la carga de escena. Hay veces que funciona y otras veces no, desconozco si ha sido por mi implementación o por las propias herramientas.


### Siguientes pasos

De cara a futuro, me gustaría añadir más elementos virtuales a la experiencia, además de añadir más variedad de "teteras", como por ejemplo:

* Conseguir cargar el "Global Mesh" de la escena
* Teteras reales pueden dejar caer té
* Tetera fantasma que aparece de reojo
* Diferentes texturas para las teteras
* Añadir más dificultad
* Pulir número de elementos que aparecen en escena
* Considerar zonas donde aparecen
* Añadir un diseño diferente a la mesa de selección
