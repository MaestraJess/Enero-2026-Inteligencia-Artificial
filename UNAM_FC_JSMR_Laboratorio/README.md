# Linear Regression Toolkit 📊
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📖 Descripción
Este módulo proporciona herramientas robustas para el cálculo de regresiones lineales simples y estimaciones masivas. Desarrollado para la clase de Inteligencia Artificial, enfocado en código limpio, manejo de excepciones y logging profesional.

## 🚀 Características
- **Cálculo de Regresión:** Obtención de intercepto ($a$) y pendiente ($b$) mediante mínimos cuadrados.
- **Validación Automática:** Manejo de errores para dimensiones incompatibles o varianza cero.
- **Logging Integrado:** Registro de eventos para auditoría de modelos.
- **Type Hinting:** Código totalmente tipado para una mejor experiencia de desarrollo (DX).

## 🛠️ Instalación
Para usar esta biblioteca, clona el repositorio y asegúrate de tener las dependencias necesarias:


git clone [https://github.com/tu-usuario/nombre-repositorio.git](https://github.com/tu-usuario/nombre-repositorio.git)
cd nombre-repositorio
pip install -r requirements.txt

⚖️ Licencia

Este proyecto está bajo la Licencia MIT.


Consulta el archivo LICENSE para más detalles



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

