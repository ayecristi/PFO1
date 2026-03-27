# Práctica Formativa Obligatoria 1 - Portafolio Personal

**Estudiante:** Ayelén Cristi
**Carrera:** Tecnicatura Superior en Desarrollo de Software
**Año:** 2026

### Descripción del Proyecto
Este proyecto consiste en el desarrollo de un portafolio personal interactivo de una sola página (One-Page) para la materia 'Frontend'. El objetivo es aplicar conocimientos fundamentales de HTML5 y CSS3, enfocándose en la estructura semántica, el uso de layouts modernos como Flexbox y Grid, y la personalización estética. El diseño elegido tiene una fuerte inspiración "Cyberpunk" o "Dark Wireframe", simulando una terminal de comandos clásica para reflejar mi perfil técnico como desarrolladora Full Stack.

---

### Checklist - Práctica Formativa Obligatoria 1

#### • Estructura del Proyecto:
- [x] Archivo "index.html" ubicado en la raíz.
- [x] Carpeta "css" que contenga el archivo "styles.css".
- [x] Carpeta "img" para recursos gráficos.
- [x] Archivo "README.md" creado, que incluya una breve descripción del TP y este checklist.

#### • Repositorio y Publicación:
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [x] URL Repositorio: https://github.com/ayecristi/PFO1
- [x] URL Vercel: https://pfo-1-git-main-ayecristis-projects.vercel.app/

#### • Uso de Google Fonts:
- [x] Enlace a Google Fonts incluido en la sección "head" del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] Elegí 'Space Mono' de Google Fonts porque mi portafolio tiene una estética Cyberpunk/Tech. Esta tipografía monoespaciada simula una terminal de comandos o un editor de código, lo cual refuerza visualmente mi perfil técnico y contrasta perfectamente con la grilla oscura de fondo y los colores neón.

#### • HTML:
- [x] El documento inicia con la declaración DOCTYPE y usa el atributo lang="es".
- [x] Se han incluido las metaetiquetas obligatorias: charset y viewport.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en "main":**
- [x] Barra de navegación ("nav") presente y contiene al menos 3 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

#### • CSS:
- [x] Existe el archivo "styles.css" con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

**Layout y Organización:**
- [x] Se ha organizado el layout (especialmente en la sección "tarjetas") utilizando Flexbox o Grid.
- [x] Utilicé Flexbox en la mayoría de las secciones (navegación, presentación y tarjetas de proyectos) por su facilidad para alinear y distribuir elementos dinámicamente (`flex-wrap`). Para la sección de películas, implementé CSS Grid, ya que me permitió crear una grilla estricta de columnas que se adapta de manera automática (usando `auto-fit` y `minmax`) garantizando que las tarjetas mantengan su proporción en cualquier dispositivo.

**Estilización de Componentes:**
- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (%, rem, vh).
- [x] Se ha implementado al menos una animación o transición (efecto hover en tarjetas o botones).
- [x] Implementé un efecto de resplandor neón automático (`box-shadow` usando `currentColor`) y una traslación vertical al pasar el mouse por las redes sociales y las tarjetas de películas. Además, desarrollé una animación de entrada para una consola oculta utilizando el "Checkbox Hack" (lógica 100% CSS sin JS). Elegí estos efectos porque le dan interactividad al sitio sin romper la estética inmersiva de consola de comandos.

#### • Consideraciones Adicionales:
- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.
- [x] Se aplicaron buenas prácticas de accesibilidad (uso de atributos alt descriptivos en las imágenes).
- [x] Se añadieron comentarios adicionales donde se describen decisiones de diseño.