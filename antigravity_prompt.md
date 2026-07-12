# Prompt para Antigravity: Generar Presentación Tipo Prezi "Ergonomía del Juego"

Puedes copiar y pegar este prompt en una nueva conversación con Antigravity para regenerar o construir una presentación similar desde cero.

```markdown
Por favor, crea una presentación web interactiva auto-contenida en un único archivo `index.html` bajo el tema **"Dispositivos de interacción en videojuegos"**, simulando la experiencia de navegación de **Prezi** (un lienzo infinito en 2D donde la cámara hace zoom, paneos y rotación fluida al cambiar de diapositiva).

### 1. Datos para la Portada (Slide 1):
- **Título Principal:** Ergonomía del Juego
- **Subtítulo:** Dispositivos de Interacción
- **Curso/Asignatura:** Experiencia de Usuario
- **Autores:** 
  - David Alessandro Contreras Baide (124390076)
  - Carlos Francisco Mejía Molina (124390052)
  - Cesar Obdulio Regalado Portillo (124390069)
- **Fecha:** 12 de Julio de 2026

### 2. Estructura y Contenido (12 Diapositivas Obligatorias):
El contenido debe vincular conceptos académicos del libro obligatorio **Mondelo, P. R. (2001). Ergonomía 4: El trabajo en oficinas** adaptándolos al gaming:
1. **Portada:** Estilo HUD de videojuego premium.
2. **Ergonomía y Videojuegos:** Definición de ergonomía (adaptar máquina al humano, Mondelo 2001) y su rol físico/cognitivo en gaming.
3. **Canales de Interacción:** Clasificación de Entrada (mandos, teclados, giroscopios) y Salida (pantallas, háptica, audio espacial).
4. **Mando de Consola (Gamepad):** Relación con la "palanca de control" (Mondelo p. 47: dimensiones, bimanualidad, botones) y diseño anatómico para el rango percentil 5-95.
5. **Teclado y Ratón Gamer:** Requisitos del teclado (Mondelo p. 43: inclinación, switches mecánicos, reposamuñecas) y del ratón (percentil 5, APM y prevención de RSI/túnel carpiano).
6. **Confort Visual en PVD (Pantallas):** Prevención de fatiga visual o astenopia (Mondelo p. 63), uso de tasas de refresco altas (144Hz+) para eliminar centelleos, control de deslumbramientos y contraste.
7. **Riesgos Biomecánicos:** Lesiones comunes en gaming (Síndrome del Túnel Carpiano, tenosinovitis de De Quervain, dolor lumbar y cervical) y medidas de prevención.
8. **Ergonomía del Software (HCI):** Adaptación de los 7 principios de diálogo (Mondelo p. 60) al diseño de interfaces (UI/UX) de videojuegos.
9. **Háptica y Audio Espacial:** Retroalimentación táctil de alta definición (DualSense) y audio en 3D (HRTF) para reducir carga cognitiva.
10. **El Futuro de la Interacción:** Realidad Virtual (cinetosis y conflicto sensorial), BCI (interfaces cerebro-computador) y accesibilidad universal (Xbox Adaptive Controller).
11. **Conclusiones:** La ergonomía como balance entre salud y rendimiento.
12. **Referencias:** Bibliografía en formato APA incluyendo el material obligatorio.

### 3. Requerimientos Técnicos y de Diseño:
- **Estética Cyberpunk/Gamer Premium:** Fondo azul cósmico oscuro (`#030712`), tipografía google font 'Outfit', gradientes e iluminaciones de neón en cian y magenta, y efectos glassmorphism.
- **Motor Prezi (JS/CSS):** 
  - El contenedor `#canvas` debe usar transiciones CSS y transformaciones `translate(50vw, 50vh) scale(S) rotate(R) translate(-X, -Y)` para centrar perfectamente cualquier slide en la pantalla.
  - Implementar cálculo responsivo dinámico en la función de zoom para que el slide activo se ajuste automáticamente a cualquier tamaño de pantalla.
- **Controles HUD integrados:**
  - Botones de "Siguiente", "Anterior", "Mapa" (zoom out completo para vista de pájaro de todas las diapositivas).
  - Teclas rápidas asociadas (Flecha Derecha / Espacio para siguiente, Flecha Izquierda para anterior, Esc para mapa).
  - Un mini-mapa en la esquina inferior derecha que muestre la disposición de los slides en el plano 2D y permita hacer clic para ir a ellos.
  - Sidebar desplegable con el índice de diapositivas para acceso rápido.
  - Opción de reproducción automática (Autoplay) con intervalo de 7 segundos.
- **Gráficos e Ilustraciones:**
  - Incluir esquemas vectoriales SVG interactivos (diagrama de bucle humano-máquina, diagramas de ángulos de muñeca, esquemas de HUD e interfaces de juego).
  - Referenciar imágenes locales en la carpeta `images/` para diagramas complejos (`images/ergonomic_gaming_setup.png`, `images/ergonomic_controller_design.png` y `images/visual_fatigue_screen.png`).
```
