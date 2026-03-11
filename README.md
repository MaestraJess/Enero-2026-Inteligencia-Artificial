# Búsqueda primero en profundidad (DFS)
Si el BFS es como una onda en un estanque, el DFS (Búsqueda en Profundidad) es como un explorador en un laberinto que decide seguir un camino hasta que choca con una pared antes de retroceder.

*Pseudocódigo*

Existen dos formas de hacerlo: con una pila explícita o mediante recursividad (que usa la pila del sistema).


DFS(Grafo, NodoActual, Visitados)

    Insertar NodoActual en Visitados
    
    PROCESAR NodoActual (imprimir o guardar)  
    
    PARA cada Vecino de NodoActual:
    
        SI Vecino no está en Visitados:
        
            DFS(Grafo, Vecino, Visitados)  // Llamada recursiva


