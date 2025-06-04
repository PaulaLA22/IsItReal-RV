# IsItReal

En esta experiencia de realidad mixta en gravedad 0 tienes un único propósito: contar cuantas teteras hay en la habitación. Para ello, deberás seleccionar una de las cartas con el número que te proponen, ¿podrás cumplir con el objetivo?

### Cómo jugar

> **AVISO:** Al hacer uso de *herramientas experimentales*, puede que la aplicación se cierre al iniciar la experiencia o al volver a escanear la sala (actualizarla). Si esto sucede, vuelve a abrir la aplicación sin actualizar la habitación desde la misma, puedes hacerlo desde la configuración de las gafas.
Si aparece el mensaje "Could not load MR Scene Model.", puede que Unreal falle en cargar la escena.

Los controles son sencillos: se puede interactuar con los objetos con tu mano izquierda, pudiendo coger los objetos virtuales con el dedo índice y el pulgar (pinch).

![image](Video/pinch.png)

Cuando sepas la respuesta a la pregunta que se te propone, deberás escoger la carta con la respuesta y dejarla sobre la mesa. ¡TEN CUIDADO! Algunos objetos no se consideran REALES, deberás averiguar si lo son.

### Licencias
Todos los assets han sido desarrollados por mí. Si se quieren hacer uso de ellos, contactad conmigo.

## Entrevista

### Proceso de creación

P: **¿Qué dificultades has encontrado durante el desarrollo? ¿Cómo las has resuelto?**

La principal dificultad del desarrollo de esta experiencia ha sido el trabajar con herramientas experimentales. La realidad mixta de Meta va evolucionando y actualizandose constantemente en el momento de la creación de este proyecto, impidiendo que sea un proceso suave.
Para resolver estos problemas, he optado por quedarme con una versión específica del plugin MRUK e intentar adaptarlo a las necesidades de las gafas.

Un problema que no he logrado aplacar ha sido el de la carga de escena. Hay veces que funciona y otras veces no, desconozco si ha sido por mi implementación o por propio Unreal.


### Siguientes pasos

De cara a futuro, me gustaría añadir más elementos virtuales a la experiencia, además de añadir más variedad de "teteras", como por ejemplo:

* Teteras reales pueden dejar caer té
* Tetera fantasma que aparece de reojo
* Diferentes texturas para las teteras
* Añadir más dificultad
* Pulir número de elementos que aparecen en escena
* Considerar zonas donde aparecen
* Añadir un diseño diferente a la mesa de selección
