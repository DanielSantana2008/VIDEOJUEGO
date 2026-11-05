# Diagramas de nuestro videojuego

En esta carpeta guardamos dos diagramas que hicimos para organizar nuestro videojuego sobre la contaminación del agua y la supervivencia de los peces. Nuestro proyecto está relacionado con el ODS 14: Vida submarina.

Al empezar una partida, el juego nos asigna un pez al azar; nosotros no lo escogemos. Tenemos que buscar comida para crecer, evitar la basura y sobrevivir a los peligros del mar. Cuando el pez alcanza su tamaño máximo, pasamos a controlar uno más grande. Al final llegamos al tiburón tigre y peleamos por el territorio.

## Diagrama de casos de uso

**Archivo:** `casos-de-uso.mmd`

Lo hicimos con la sintaxis de diagrama de flujo de Mermaid para que se pueda abrir en versiones más antiguas del editor. Representa los casos de uso con recuadros redondeados, aunque no tiene la notación UML estricta.

Aquí mostramos lo que el jugador puede hacer: empezar una partida, ver las instrucciones, mover al pez, buscar comida, evitar la basura, revisar su vida y crecimiento, pausar, volver a jugar y participar en la pelea final. También incluimos algunas cosas que pasan dentro del juego, como recibir un pez al azar o pasar a uno más grande.

Este diagrama nos ayuda a entender qué funciones necesita nuestro videojuego y cómo va a interactuar el jugador con ellas.

## Diagrama de clases

**Archivo:** `diagrama-de-clases.mmd`

Aquí proponemos cómo dividir el programa en partes para que sea más fácil desarrollarlo:

- **Partida:** inicia, pausa y reinicia el juego.
- **Pez:** guarda su vida, tamaño y crecimiento, y permite moverlo y alimentarlo.
- **TipoDePez:** contiene la información de cada especie.
- **Mar:** representa el lugar donde aparecen la comida y la basura.
- **Comida:** ayuda al pez a crecer.
- **Basura:** puede quitarle vida al pez.
- **PeligroEspecial:** agrupa otros peligros que pueden aparecer durante la partida.
- **PeleaFinal:** maneja la pelea entre tiburones.
- **Resultado:** muestra cómo terminó la partida y un mensaje educativo.


## ¿En qué nos basamos?

Usamos el documento de requisitos de nuestro proyecto. Tomamos las funciones principales: iniciar la partida, alimentarse, crecer, recibir daño por contaminación, cambiar de pez, enfrentar algunos peligros y llegar a la pelea final. Para no hacer los diagramas demasiado complicados, agrupamos algunos detalles bajo nombres más sencillos. Y utilizamos el objetivo 14 de la ODS.
