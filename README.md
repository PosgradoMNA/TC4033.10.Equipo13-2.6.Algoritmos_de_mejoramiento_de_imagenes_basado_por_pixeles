# TC4033.10.Equipo13-Algoritmos_de_mejoramiento_de_imagenes_basado_por_pixeles

## Alumnos

- Víctor Hugo Avila Felipe
- Erik López Hernández
- César Iván Pedrero Martínez
- Carlos Alberto Reynoso González
- Hugo Enrique Solano Ortega

## Instrucciones

Para esta actividad se requiere:

1. Ingresar a Canvas y descargar el proyecto en Notebook Download Notebook.
2. Revisar los ejercicios propuestos antes de codificar e identificar las secciones de libro o de las diapositivas que te puedan servir como soporte.
3. El proyecto con el Google Collab modificado y las respuestas a los ejercicios se deben convertir en PDF y también en archivo comprimido y entregarse vía Canvas.

Los ejercicios que deben agregarse a este proyecto serán los siguientes:

1. Investiga e implementa el método tile-based histogram equalization. En estos métodos, la imagen se particiona en diferentes ventanas (i.e. mosaicos) y los histogramas se calculan de forma independiente, aplicando la corrección sobre cada ventana. Existe un compromiso entre el tamaño de la ventana y la complejidad computacional, por lo cual es más complejo que el método simple. Implementa esta versión y realiza algunas pruebas variando el tamaño de la ventana. Otro inconveniente es que se puede observar posibles diferencias entre los el contraste de los bloques, ¿cómo podría mejorarse?
2. Investiga e implementa un método sencillo del Sliding Window Adaptive Histogram Equalization (SWAHE) y compara algunas imágenes con diferentes tipos de imágenes.
3. Investiga cómo funciona el algoritmo CLAHE (contrast limited adaptive histogram equalization) y realiza una implementación (puede ser usando la implementación de OpenCV). Prueba sobre diferentes tipos de imágenes y compara con el método de ecualización de histogramas básico. Provee una breve descripción del método a partir de una  investigación bibliográfica.
