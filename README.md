# Trabajo Práctico 1 - Aprendizaje Automático 2

Este repositorio contiene las soluciones a tres problemas prácticos sobre **modelos de aprendizaje profundo**, implementados en **Python** y **Google Colab**.

---

## Problema 1 - Predicción del Rendimiento Académico (Regresión)

**Descripción:**  
Se construye un modelo de **regresión con redes neuronales** para predecir el **índice de rendimiento académico** de estudiantes universitarios a partir de variables como horas de estudio, horas de sueño, puntajes previos, entre otras.

**Contenido:**  
- Análisis exploratorio y preprocesamiento del dataset.  
- Definición, entrenamiento y evaluación del modelo de red neuronal.  
- Visualización de resultados y métricas de desempeño (MAE, MSE, R²).  

**Archivo principal:**  
`PROBLEMA_1_CICORIA_RICCI.ipynb`

---

## Problema 2 - Clasificación de Gestos (Piedra, Papel o Tijeras)

**Descripción:**  
Implementación de un sistema de clasificación de gestos utilizando **MediaPipe** para la detección de gestos de la mano y una **red neuronal densa** para la clasificación.

**Estructura:**  
1. `record-dataset.py` → Captura gestos de la mano y genera el dataset.  
2. `train-gesture-classifier.py` → Entrena la red neuronal con los datos recolectados.  
3. `rock-paper-scissors.py` → Ejecuta el sistema en tiempo real con cámara web.

**Extras:**  
📁 Carpeta `TEST PROBLEMA2/` con capturas del funcionamiento del sistema.


---

## Problema 3 - Clasificación de Imágenes de Escenas Naturales

**Descripción:**  
Se entrena un modelo de **clasificación de imágenes** con diferentes arquitecturas:
- Modelo con capas densas.  
- Modelo con capas convolucionales.  
- Modelo con bloques residuales identidad.  
- Modelo con **Transfer Learning** (backbone preentrenado de TensorFlow).  

**Categorías:**  
`buildings`, `forest`, `glacier`, `mountain`, `sea`, `street`

**Archivo principal:**  
`PROBLEMA_3_CICORIA_RICCI.ipynb`

---

## Tecnologías Utilizadas

- Python 3.x  
- TensorFlow / Keras  
- NumPy / Pandas / Matplotlib / Seaborn  
- MediaPipe
- OpenCV

---

## Autores
**Cicoria, Ignacio - Ricci, Guillermo**

