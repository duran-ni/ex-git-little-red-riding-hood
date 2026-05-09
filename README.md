# ex-git-little-red-riding-hood

# Análisis de la Estructura
Es un diseño de maquetación en zig-zag (alternando imagen y texto) para que se vea más dinámico. La estructura técnica se divide así:

# 1. Header (Navegación)

Menú: Enlaces a "El viaje", "El bosque", "El lobo" y "El final".

Icono de un libro a la derecha del todo.

# 2. Hero Section (Portada)
Un contenedor principal con el títlo "Caperucita Roja" y una breve introducción sobre el autor del libro.

Debajo, un espacio reservado para una imagen representativa del cuento.

# 3. Cuerpo Narrativo (Capítulos)
La historia se divide en 4 secciones con la estructura grid/flexbox:

Capítulo 1: La partida hacia la casa de la abuela

Disposición: Texto a la izquierda, imagen a la derecha.

Contenido: Introducción de Caperucita y el encargo de su madre.

Capítulo 2: El encuentro con el lobo

Disposición: Texto a la derecha, imagen a la izquierda.

Contenido: El primer contacto con el lobo.

Capítulo 3: El engaño en la cabaña

Disposición: Texto a la izquierda, imagen a la derecha.

Contenido: El momento del engaño en la casa de la abuela.

Capítulo 4: El valiente cazador y el final feliz

Disposición: Texto a la derecha, imagen a la izquierda.

Contenido: Resolución del conflicto y final feliz.

Añade un botón "Leer más leyendas"

# 4. Footer (Pie de página)
Información de copyright, enlaces secundarios de "Archives",  y "Story Index" y "Privacy"
Icono de un libro a la derecha del todo.

# Plan de Implementación Técnica
HTML Semántico: Usaré etiquetas <header>, <main>, <section> para cada capítulo y <footer>.

CSS Layout: Utilizaré Flexbox o CSS Grid para lograr el efecto de alternancia entre texto e imágenes que se ve en el diseño.

Estética: Se aplicará una paleta de colores minimalista (blanco, negro y gris) como se ve en el wireframe, o se añadirá color según la temática del cuento.