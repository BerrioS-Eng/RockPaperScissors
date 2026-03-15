# Rock Paper Scissors - Juego Inmersivo con Gestos

Juego de Piedra, Papel o Tijera que utiliza la cámara web y reconocimiento de gestos en tiempo real con [MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/guide). No necesitas teclado ni mouse — solo tus manos.

## Demo

1. Permite el acceso a la cámara web.
2. Haz **pulgar arriba** (👍) para iniciar una ronda.
3. Después de la cuenta regresiva de 5 segundos, muestra tu jugada con la mano:
   - ✊ **Puño cerrado** → Piedra
   - ✋ **Palma abierta** → Papel
   - ✌️ **Victoria** → Tijera
4. El resultado se muestra en pantalla con efectos de confeti si ganas.

## Tecnologías

- **MediaPipe Gesture Recognizer** — detección de gestos de mano en tiempo real vía WebAssembly
- **Tailwind CSS** — estilos utilitarios con efecto glassmorphism
- **Canvas Confetti** — animación de confeti al ganar
- **JavaScript (ES Modules)** — lógica del juego sin frameworks

## Requisitos

- Navegador moderno con soporte para WebRTC (Chrome, Edge, Firefox)
- Cámara web
- Conexión a internet (las dependencias se cargan desde CDN)

## Uso

Abre `index.html` directamente en el navegador.
