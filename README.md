# Procesamiento Digital de Imágenes con Python 🖼️

Este proyecto forma parte de una práctica académica y consiste en explorar
diferentes librerías de Python para el procesamiento digital de imágenes,
aplicando técnicas variadas sobre distintos tipos de datos visuales.

Se trabajó con arreglos numéricos, imágenes obtenidas de internet, fotografías
locales y una secuencia de imágenes extraída de un video.

## 🧠 Descripción

El objetivo principal es comprender cómo una imagen puede representarse como
datos numéricos y cómo distintas técnicas permiten modificar, analizar o
resaltar información visual.

Durante el desarrollo de la práctica se realizaron los siguientes pasos
principales:

- Representación de imágenes como arreglos numéricos.
- Carga y procesamiento de imágenes externas y locales.
- Aplicación de transformaciones visuales sobre fotografías reales.
- Generación de imágenes mediante dibujo digital.
- Análisis de cambios en una secuencia de imágenes (video).

## 🛠️ Librerías utilizadas

Para el desarrollo del notebook se emplearon distintas librerías, cada una con
un propósito específico:

- **NumPy**: manejo de arreglos y operaciones matemáticas.
- **OpenCV (cv2)**: procesamiento de imágenes y video.
- **Pillow (PIL)**: creación y edición de imágenes mediante dibujo.
- **Matplotlib**: visualización de imágenes y resultados.

## 🧪 Técnicas aplicadas

Se implementaron cinco técnicas distintas, cada una aplicada a un tipo de dato
diferente, con el fin de cubrir todos los requerimientos de la práctica:

- Tratamiento directo de un arreglo que simula una imagen.
- Procesamiento de una imagen obtenida de internet (descargada previamente).
- Aplicación de transformaciones sobre una fotografía local.
- Generación de una imagen desde cero utilizando dibujo digital.
- Comparación de frames separados en el tiempo dentro de un video.

Cada técnica permitió observar cómo cambia la información visual dependiendo
del tipo de entrada y del método aplicado.

## 📊 Resultados generales

Los resultados muestran que las imágenes digitales pueden manipularse
directamente como matrices de datos y que pequeñas modificaciones numéricas
producen cambios visibles.

En el caso del video, se observó que comparar frames consecutivos no siempre
es suficiente para detectar cambios, por lo que fue necesario analizar frames
más alejados en el tiempo para identificar claramente el efecto de zoom.

La generación de imágenes mediante código demostró que no solo es posible
procesar imágenes existentes, sino también crear contenido visual de manera
programática.

## 📁 Requisitos

Para ejecutar el notebook correctamente es necesario contar con:

- Python 3.x
- Librerías:
  - `numpy`
  - `opencv-python`
  - `pillow`
  - `matplotlib`

Puedes instalarlas con:

```bash
pip install numpy opencv-python pillow matplotlib
