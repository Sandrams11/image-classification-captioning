# 🖼️ IBM AI Course — Image Classification & Captioning Final Project

Este repositorio contiene el cuaderno **`Final_Project_Classification_and_Captioning.ipynb`**, desarrollado durante el curso de **IBM Introduction to Deep Learning & Neural Network with Keras**.  
El proyecto combina dos tareas principales de *Deep Learning*:
1. Clasificación de imágenes utilizando una red convolucional (CNN).
2. Generación automática de descripciones (Image Captioning) mediante una red neuronal combinada CNN + LSTM.

---

## 🎯 Objetivo del proyecto
Desarrollar un modelo que:
- Clasifique imágenes en diferentes categorías visuales.
- Genere un texto descriptivo (caption) que describa el contenido de cada imagen.

Este tipo de sistemas es una aplicación práctica de **Computer Vision + Natural Language Processing (NLP)**, base de muchas herramientas de accesibilidad y etiquetado automático de imágenes.

---

## 🗂️ Estructura del repositorio
- `Final_Project_Classification_and_Captioning.ipynb` → Cuaderno principal con todo el flujo del proyecto.
- `requirements.txt` → Dependencias opcionales para reproducir el entorno.
- `.gitignore` → Archivos a excluir del control de versiones.

---

## 🧠 Metodología resumida

### 1️⃣ Clasificación de imágenes
- Uso de un conjunto de imágenes preentrenado (por ejemplo, **MobileNet** o **ResNet** de `tensorflow.keras.applications`).
- Preprocesamiento: *resizing*, *normalización* y *data augmentation*.
- Entrenamiento de una capa *dense* final para clasificación multiclase.
- Evaluación con métricas: **accuracy**, **loss**, **precision**, **recall**.

### 2️⃣ Image Captioning
- Extracción de **features visuales** desde una CNN preentrenada (como InceptionV3).
- Tokenización del texto (descripciones).
- Uso de una **red LSTM** para generar captions palabra a palabra.
- Entrenamiento supervisado con pares `(imagen, caption)`.
- Generación de resultados: predicción de captions para nuevas imágenes.

---

## 🧩 Tecnologías utilizadas
- **Python 3.x**
- **TensorFlow / Keras**
- **NumPy, Pandas**
- **Matplotlib**
- **NLTK** (para tokenización del texto)
- **Jupyter Notebook**

---
