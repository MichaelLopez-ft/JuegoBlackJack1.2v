# Juego BlackJack
## Cambios realizados versión 1.2

Se realizaron las siguientes modificaciones en el código para mejorar la funcionalidad del juego en la clase JuegoDeCartas:

1. **Número de Jugadores a elección del usuario**  
   Se añadió la capacidad para que el usuario ingrese el número de jugadores antes de iniciar el juego. Anteriormente, el número de jugadores era fijo en el main.  
   **Cambio realizado en:**  
   - **Líneas 10-13:** Solicitud de entrada para el número de jugadores.  
   - **Líneas 15-19:** Adición de jugadores al juego en base a la entrada del usuario.

2. **Número de Rondas a elección del usuario**  
   Ahora el usuario puede definir cuántas rondas desea jugar antes de comenzar el juego. 
   **Cambio realizado en:**  
   - **Líneas 22-24:** Solicitud de entrada para el número de rondas.  
   - **Líneas 26-27:** Asignación del número de rondas a la variable `numeroDeRondas`.

3. **Modificación en el Constructor**  
   El constructor de la clase `JuegoDeCartas` ahora no recibe parámetros. En cambio, solicita la entrada del usuario para el número de jugadores y el número de rondas dentro del constructor.  
   **Cambio realizado en:**  
   - **Líneas 6-8:** Eliminación de parámetros del constructor.  
   - **Líneas 10-29:** Solicitud de entrada para el número de jugadores y el número de rondas dentro del constructor.

