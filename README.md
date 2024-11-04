# Calibración de Cámara con Corrección de Distorsión usando OpenCV

Este repositorio contiene un proyecto de calibración de cámaras digitales basado en el uso de un patrón de tablero de ajedrez y la biblioteca OpenCV. La calibración permite corregir distorsiones radiales y tangenciales en las imágenes para obtener mayor precisión geométrica, ideal para aplicaciones en visión computacional y realidad aumentada.

## Características del Proyecto
- **Detección y Refinamiento de Esquinas**: Detección precisa de puntos de referencia en el tablero.
- **Cálculo de Parámetros de Calibración**: Obtención de matriz de cámara, coeficientes de distorsión y vectores de rotación y traslación.
- **Corrección de Distorsión**: Dos métodos de corrección con `cv2.undistort` y `cv2.remap`.
- **Evaluación de Precisión**: Cálculo del error de reproyección para validar la calidad de la calibración.

## Requisitos
- Python
- OpenCV
- Google Colab (opcional)

Este proyecto es ideal para quienes buscan una solución de calibración de cámara accesible y efectiva en Python.
