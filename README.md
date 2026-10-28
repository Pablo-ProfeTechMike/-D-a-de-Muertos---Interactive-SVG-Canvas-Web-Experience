# 🌼 Día de Muertos - Interactive SVG Canvas & Web Experience

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-333333?style=for-the-badge&logo=soundcharts&logoColor=white)

Una aplicación web interactiva que rinde tributo a la tradición mexicana del **Día de Muertos** mediante el trazado y dibujo vectorial animado en tiempo real de tres elementos icónicos: la **Calaverita de Azúcar**, el **Pan de Muerto** y la **Ofrenda Tradicional**.

---

## 🚀 Características Principales

- 💀 **3 Ilustraciones Vectoriales Interactiva:** Alterna fluidamente entre la Calaverita, el Pan de Muerto y el Altar/Ofrenda de 3 niveles.
- 🎨 **Convertidor de Primitivas SVG a Path:** Procesamiento automático de elementos geométricos (`<rect>`, `<circle>`, `<line>`, etc.) a curvas `<path>` para un renderizado uniforme.
- ⚡ **Motor de Animación SVG:** Manipulación dinámica de `stroke-dashoffset` y `stroke-dasharray` mediante funciones de aceleración (`easeInOutQuad`).
- 🌈 **Paletas de Colores Mexicanas:** Modos de coloreado tradicional y por secciones (*Cempasúchil*, *Alebrije Neón*, *Catrina Elegante*, *Noche Mística*, *Flor de Terciopelo*).
- ✨ **Partículas y Ambiente:** Canvas 2D en segundo plano que simula la caída continua de pétalos de cempasúchil y chispas de azúcar.
- 🎵 **Sintetizador Web Audio API:** Efectos sonoros integrados que reproducen acordes y *chimes* al finalizar cada trazado.
- 📱 **Diseño Totalmente Responsive:** Adaptado para dispositivos móviles, tablets y monitores de escritorio.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & SVG Vector Graphics:** Estructura semántica e ilustraciones compuestas.
- **CSS3 / Sass (SCSS):** Estilos festivos, animaciones clave, variables CSS y layouts adaptativos.
- **JavaScript (ES6+) & jQuery:** Lógica de conversión de objetos SVG, control de tiempos de animación y manipulación del DOM.
- **HTML5 Canvas 2D Context:** Motor de renderizado de partículas (pétalos de cempasúchil).
- **Web Audio API:** Generación nativa de audio sintetizado sin librerías externas pesadas.

---

## 📂 Estructura del Proyecto

```text
├── index.html        # Estructura principal, SVGs y vistas de navegación
├── styles.css        # Estilos, temas neón, paletas y maquetación responsive
├── script.js        # Motor de animación SVG, lógica de audio y partículas en Canvas
└── README.md         # Documentación del proyecto
