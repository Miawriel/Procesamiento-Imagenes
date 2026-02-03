# Procesamiento Digital de Imágenes en Python

Este repositorio contiene una práctica desarrollada en **Jupyter Notebook** donde se exploran diferentes librerías de Python para el procesamiento digital de imágenes.  
Se aplican distintas técnicas sobre varios tipos de datos visuales, cumpliendo con los requerimientos solicitados en la actividad.

---

## 📌 Objetivo de la práctica

Explorar y aplicar técnicas de procesamiento digital de imágenes utilizando **al menos tres librerías diferentes en Python**, trabajando con:

- Un arreglo numérico
- Una imagen obtenida de internet
- Una fotografía local
- Una secuencia de imágenes (video)

El objetivo es comprender cómo las imágenes pueden ser representadas, transformadas y analizadas mediante código.

---

## 🧰 Librerías utilizadas

Durante el desarrollo del notebook se utilizaron las siguientes librerías:

- **NumPy**: para el manejo de arreglos y representación matricial de imágenes.
- **OpenCV (cv2)**: para el procesamiento de imágenes y video.
- **Pillow (PIL)**: para la creación y manipulación de imágenes mediante dibujo.
- **Matplotlib**: para la visualización de resultados.

---

## 🧪 Técnicas aplicadas

A lo largo del notebook se implementaron cinco técnicas distintas, cada una aplicada a un tipo de dato diferente:

1. **Tratamiento de un arreglo**  
   Representación de una imagen como una matriz y modificación directa de sus valores.

2. **Procesamiento de una imagen de internet**  
   Carga y análisis de una imagen externa descargada previamente para evitar problemas de acceso HTTP.

3. **Procesamiento de una fotografía local**  
   Aplicación de transformaciones sobre una imagen real almacenada localmente.

4. **Generación de imagen mediante dibujo digital**  
   Creación de una imagen desde cero utilizando Pillow e ImageDraw.

5. **Procesamiento de una secuencia de imágenes (video)**  
   Comparación de frames separados en el tiempo para detectar cambios visuales producidos por el movimiento y el zoom.

---

## 🔍 Resultados y observaciones

- Se observó que las imágenes digitales pueden manipularse directamente como arreglos de datos.
- Las imágenes reales y los videos presentan mayor complejidad debido al ruido, la iluminación y el movimiento.
- En el caso del video, fue necesario comparar frames distantes para que los cambios fueran claramente perceptibles.
- La generación de imágenes mediante código demuestra que no solo se pueden procesar imágenes existentes, sino también crear nuevas.

---

## 📂 Contenido del repositorio

- `Procesamiento_Imagenes.ipynb` (Notebook principal con el desarrollo de la práctica)
- Imágenes y video utilizados para las pruebas
- `README.md`

---

## ✅ Conclusión

Esta práctica permitió comprender de manera práctica cómo funcionan distintas técnicas de procesamiento digital de imágenes y cómo pueden aplicarse a diferentes tipos de datos visuales.  
El uso de múltiples librerías mostró que cada herramienta tiene fortalezas específicas, y que la correcta selección de técnicas depende del tipo de información que se desea analizar.

---

📎 *Repositorio desarrollado como parte de una práctica académica.*
