## Akinator con Árboles Binarios AVL

Este proyecto implementa un juego de adivinanza similar a Akinator utilizando árboles binarios AVL para gestionar preguntas y respuestas.

### Estructura del Árbol
- **Nodos:** Representan preguntas o respuestas.
- **Balanceo:** Se asegura que la altura de los subárboles difiera como máximo en uno.

### Funcionamiento
1. **Inicio del Juego:** El usuario piensa en un personaje, y el árbol guía con preguntas.
2. **Navegación:** Se desplaza por el árbol basado en las respuestas (sí/no).
3. **Adivinanza:** Al llegar a un nodo hoja, se adivina el personaje. Se actualiza el árbol si es incorrecto.
4. **Actualización Dinámica:** El árbol se reestructura automáticamente para optimizar el rendimiento.

### Ventajas
- **Rápido Acceso:** Estructura balanceada permite acceso y búsqueda rápidos.
- **Aprendizaje Automático:** Se adapta y mejora con cada partida.
