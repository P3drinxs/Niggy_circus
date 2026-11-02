Circus Niggy

Videojuego arcade de plataformas desarrollado con HTML5, CSS3 y JavaScript.

Circus Gato es un videojuego de supervivencia infinita (endless runner) protagonizado por Niggy, una gata que debe superar obstáculos en un escenario circense.

Inspirado en clásicos como Circus Charlie y en la mecánica de supervivencia del dinosaurio de Google Chrome, el juego combina gráficos pixel art, animaciones, música y dificultad progresiva.

El objetivo es superar tantos obstáculos como sea posible y conseguir la puntuación más alta.

Características principales

Modo infinito: el juego continúa hasta que el personaje colisiona con un obstáculo.

Dificultad progresiva: la velocidad aumenta conforme se acumulan puntos.

Obstáculos animados: aros de fuego y llamas con detección de colisiones.

Escenario pixel art: graderías, espectadores animados y elementos decorativos circenses.

Desplazamiento del escenario: suelo animado y sincronizado con la velocidad de los obstáculos.

Banda sonora: música y efectos de sonido integrados.

Efectos visuales: animación de explosión al perder.

Controles multiplataforma: compatible con teclado y controles táctiles.

Modo depuración: visualización opcional de hitboxes para facilitar el desarrollo.

Controles

Computador

Tecla

Función

Flechas izquierda/derecha

Movimiento horizontal

Z / Espacio / Flecha arriba

Saltar

H

Mostrar u ocultar hitboxes

M

Activar o desactivar música

R

Reiniciar partida

Dispositivos móviles

El juego dispone de controles táctiles para desplazarse horizontalmente y saltar.

También incluye un botón para mostrar u ocultar las hitboxes durante las pruebas.

Sistema de puntuación y dificultad

Cada obstáculo superado otorga 10 puntos.

La dificultad aumenta progresivamente mediante dos mecanismos:

Velocidad de desplazamiento:

Velocidad inicial: 260 píxeles por segundo.

Incremento: 50 píxeles por segundo cada 20 puntos.

La velocidad del suelo permanece sincronizada con la de los obstáculos.

Frecuencia de obstáculos:

Intervalo inicial aleatorio entre 1,65 y 2,30 segundos.

Cada 100 puntos se reduce progresivamente el tiempo entre apariciones.

Se establece un intervalo mínimo para evitar una frecuencia excesiva.

Al colisionar con un obstáculo, se activa una explosión visual y sonora. La partida se reinicia automáticamente después de cuatro segundos.

Tecnologías utilizadas

Tecnología

Aplicación

HTML5

Estructura del videojuego

CSS3

Interfaz y controles táctiles

JavaScript

Física, lógica y animaciones

Canvas API

Renderizado gráfico 2D

PNG

Sprites, escenarios y elementos visuales

MP3 / WAV

Música y efectos de sonido

El proyecto utiliza JavaScript nativo y no depende de motores de videojuegos ni frameworks externos.

Instalación

Clonar el repositorio:

git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git

Abrir la carpeta descargada y ejecutar el archivo index.html desde un navegador compatible.

También es posible publicar el proyecto mediante GitHub Pages o Netlify para jugar directamente desde internet.

Estructura del proyecto

circus-gato/
├── index.html
├── assets/
│   ├── gato_0.png
│   ├── gato_1.png
│   ├── gato_2.png
│   ├── aro_fuego_0.png
│   ├── aro_fuego_1.png
│   ├── aro_fuego_2.png
│   ├── fuego_0.png
│   ├── ...
│   ├── publico_base.png
│   ├── publico_delta1.png
│   ├── publico_delta2.png
│   ├── cenefa_superior.png
│   ├── separador_gradas.png
│   ├── piso_scroll.png
│   ├── circus_gato_cuerdas_v3.mp3
│   └── explosion_arcade.wav
└── README.md

Estado del desarrollo

Estado actual: prototipo funcional en desarrollo.

Funcionalidades implementadas

Movimiento y salto

Sistema de colisiones

Obstáculos animados

Escenario con espectadores animados

Desplazamiento continuo del suelo

Dificultad progresiva

Sistema de puntuación

Música y efectos de sonido

Animación de derrota

Controles táctiles

Visualización de hitboxes

Posibles mejoras futuras

Incorporación de nuevos obstáculos

Menú principal

Sistema de récords persistente

Nuevas animaciones y efectos

Optimización para diferentes resoluciones

Compatibilidad ampliada con controles externos

Sobre el proyecto

Circus Gato es un proyecto personal de desarrollo de videojuegos inspirado en la estética y las mecánicas de los arcades clásicos.

El proyecto tiene como protagonista a Niggy y busca combinar una jugabilidad sencilla con dificultad progresiva, gráficos pixel art y una identidad visual propia.

Su desarrollo se realiza de manera iterativa, incorporando mejoras en la física, las colisiones, las animaciones, el sonido y la experiencia de usuario.

Circus Gato — Proyecto independiente en desarrollo.
