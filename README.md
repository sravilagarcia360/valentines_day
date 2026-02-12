    ❄️ Sorpresa Romántica

Una experiencia web inmersiva de Storytelling Digital diseñada para narrar una historia personal y realizar una propuesta interactiva de San Valentín. Este proyecto utiliza técnicas modernas de desarrollo frontend para crear una atmósfera emocional mediante animaciones fluidas y una estética inspirada en las auroras boreales.

    📸 Experiencia de Usuario (UX)

El flujo de la aplicación se divide en tres actos coreografiados:

El Álbum de Memorias: Un sistema de diapositivas estilo Polaroid que recorre momentos clave con tipografías manuscritas y emojis dinámicos.

El Clímax (Interacción): Una transición dramática hacia una noche ártica con la pregunta principal. Incluye un botón "No" con lógica de evasión (vuela cuando intentas tocarlo) para añadir un toque divertido.

La Celebración: Tras la confirmación, se activa un motor de partículas temático (❄️, ❤️, ✨, 🇮🇸) y un mensaje final personalizado: "✨ Elegirte fue mi mejor decisión ✨".

    ✨ Características Técnicas

Snow Engine (Canvas API): Sistema de partículas de alto rendimiento que simula una nevada constante mediante el contexto 2D de Canvas, asegurando fluidez incluso en dispositivos móviles.

Aurora Borealis Effect: Fondo animado mediante gradientes lineares dinámicos y filtros de desenfoque (backdrop-filter) que recrean el ambiente gélido y mágico de Islandia.

Lógica de Evasión Inteligente: El botón negativo utiliza getBoundingClientRect() para calcular posiciones aleatorias seguras dentro del viewport, evitando solapamientos y asegurando que sea inalcanzable.

Responsive & Touch Ready: Implementación de Viewports flexibles y soporte para eventos táctiles, optimizado para una experiencia perfecta en iOS y Android.

    🏗️ Stack Tecnológico

Frontend: HTML5 semántico y CSS3 avanzado (Animaciones Keyframes).

Estilos: Tailwind CSS para un diseño atómico y moderno.

Lógica: Vanilla JavaScript (ES6+). Sin dependencias externas para máxima velocidad de carga.

Tipografía: Google Fonts (Dancing Script, Indie Flower, Comfortaa).

    🚀 Despliegue en GitHub Pages

Para publicar este proyecto y compartir el link:

Sube tu archivo index.html a un nuevo repositorio en GitHub.

Ve a la pestaña Settings > Pages.

En la sección "Build and deployment", selecciona la rama main y haz clic en Save.

Tu sitio estará disponible en: https://tu-usuario.github.io/nombre-del-repo/.

    ⚙️ Personalización

Puedes modificar la historia editando el array storyPages en el código fuente de tu archivo:

const storyPages = [
    { text: "Tu mensaje personalizado aquí", emoji: "❤️" },
    // Puedes añadir tantas páginas como desees
];


Desarrollado con ❤️ Sr.Avila.dev
