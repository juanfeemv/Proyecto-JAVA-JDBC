🧩 Laberinto Quiz — Proyecto por Consola

Este proyecto consiste en un juego por consola que combina un laberinto y un quiz de preguntas. El jugador comienza en la esquina superior izquierda del laberinto y debe llegar a la esquina inferior derecha, moviéndose por una cuadrícula con muros, cocodrilos y botiquines.

Para poder moverse, el jugador debe responder correctamente una pregunta dentro de un tiempo límite. Las preguntas provienen de un banco configurable y no se repiten durante la partida. Si el jugador falla o se pasa de tiempo, pierde vida y debe intentarlo de nuevo. Al entrar en una celda puede perder o recuperar vida según haya cocodrilos o botiquines.

El juego permite configurar distintos laberintos, tamaños, objetos, porcentaje de vida perdida o ganada, y tiempo máximo para responder. También permite generar disposiciones, que son diferentes distribuciones aleatorias de cocodrilos y botiquines dentro de un mismo laberinto.

La partida termina si el jugador llega a la salida, se queda sin vida o sin preguntas disponibles. Al finalizar, el juego guarda un ranking con información del usuario, laberinto, disposición, si logró salir y la vida restante.

Todo el proyecto está desarrollado siguiendo el patrón MVC, y se ejecuta completamente por consola.
