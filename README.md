# Ejercicios-Pygame2

MATERIA: GRAFICACIÓN 2-3PM
ALUMNO: CRISTIAN MIGUEL MARINES CABALLERO

sesion4_ej1.py – Rebote con velocidad variable

Simula un círculo que rebota dentro de la ventana.
Cada vez que toca un borde, su velocidad horizontal aumenta gradualmente.
El programa mantiene una animación fluida a 60 FPS usando pygame.time.Clock.

sesion4_ej2.py – Animación de pulsación

Crea un círculo que cambia su tamaño entre 20 y 50 píxeles simulando una pulsación.
Cuando alcanza el tamaño máximo o mínimo, invierte la dirección del crecimiento.
Usa un bucle principal con control de tiempo para lograr una animación suave.

sesion4_ej3.py – Simulación de gravedad

Representa una bola que cae bajo el efecto de la gravedad y rebota en el suelo.
Cada rebote reduce la velocidad vertical en un 20%, simulando pérdida de energía.
Implementa aceleración y colisiones con el borde inferior.

Sesión 5: Imágenes y sprites

Objetivo: Trabajar con imágenes, sprites y transformaciones.

sesion5_ej1.py – Ajuste de tamaño dinámico

Carga una imagen y permite al usuario cambiar su tamaño con las teclas + y -.
Mantiene la proporción original al escalar, evitando distorsiones.
Ideal para practicar el uso de pygame.transform.scale.

sesion5_ej2.py – Sprite animado

Muestra una animación basada en una hoja de sprites con varios cuadros.
Cambia de frame cada 100 ms para simular el movimiento (por ejemplo, caminar).
Aplica técnicas de recorte de imágenes y temporización.

sesion5_mini.py – Mini-proyecto: Nave con rotación

Controla una imagen (por ejemplo, una nave) que rota para apuntar hacia el ratón o joystick.
Al presionar una tecla o botón, la nave se mueve hacia adelante en la dirección actual.
Incluye manejo de rotación, escalado y movimiento de sprites.

Sesión 6: Colisiones y aplicaciones prácticas

Objetivo: Implementar detección de colisiones y crear juegos interactivos.

sesion6_ej1.py – Colisión con cambio de color

Muestra un rectángulo controlado por el jugador que cambia de color al chocar con un objetivo.
Ejemplo básico de detección de colisiones entre rectángulos.

sesion6_ej2.py – Recolección de objetos

Permite mover un rectángulo (jugador) para recoger círculos colocados aleatoriamente.
Cada vez que el jugador recoge uno, aparece otro y aumenta un contador visible en pantalla.
Usa random.randint para generar posiciones y pygame.font para mostrar puntuación.

sesion6_ej3.py – Evitar obstáculos

El jugador controla un rectángulo que debe esquivar círculos en movimiento.
Si ocurre una colisión, el juego termina o se reinicia.
Aplica colisiones dinámicas y control de movimiento.

sesion6_mini.py – Mini-proyecto: Juego de recolección y evasión

Juego completo donde el jugador maneja un sprite (por ejemplo, una nave), recolecta objetos y evita obstáculos.
Muestra un contador de puntos en la pantalla usando pygame.font.
Combina movimiento, colisiones, animaciones y manejo de imágenes.
