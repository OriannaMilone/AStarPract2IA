# AStarPract2IA
Práctica 2. Algoritmo de busqueda A* (A Star)


1. ¿Qué variable representa la lista ABIERTA?
    = La variable que representa la lista ABIERTA es la variable "openList" que es una lista de nodos que se encuentran en la lista ABIERTA.
2. ¿Qué variable representa la función g?
    = La variable que respresenta a la función g, es gScore. Esta función g, representa la distancia desde el nodo inicial hasta el nodo actual.
3. ¿Qué variable representa la función f?
    = La variable que representa a la función f, es fScore. Esta función f, representa la suma de la función g y la función h.
4. ¿Qué método habría que modificar para que la heurística representara la distancia aérea entre vértices?
    = El método que habría que modificar para que la heurística representara la distancia aérea entre vértices, es el método "heuristic_cost_estimate" que se encuentra en la clase "AStar" en la línea 40.
5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la respuesta.
    = No, no realiza la reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice, ya que la función "heuristic_cost_estimate" solo calcula la distancia entre el nodo actual y el nodo final, por lo que no se reevalua la distancia entre los nodos.

    