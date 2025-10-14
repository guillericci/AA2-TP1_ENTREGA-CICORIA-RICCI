# Trabajo Práctico - Detección Rock-Paper-Scissors (TP1 - PROBLEMA 2)

**Repositorio:** contiene los scripts necesarios para grabar un dataset de gestos de mano, entrenar un modelo de clasificación y realizar la predicción en tiempo real mediante cámara.  
**Lenguaje:** Python 3.10

---

## 📁 Estructura del repositorio
```bash

TP1/
└── PROBLEMA 2/
  ├── dataset/ # Archivos .npy generados al grabar datos (opcional)
  ├── requirements.txt # Dependencias necesarias
  ├── record_dataset.py # Script para grabar dataset
  ├── train-gesture-classifier.py # Entrena y guarda el modelo
  ├── rock-paper-scissor.py # Ejecuta la inferencia en tiempo real
  └── rps_model.h5 # Modelo entrenado (se genera automáticamente)
```
## ⚙️ Instalación

### 1️⃣ Crear un entorno virtual

Es recomendable aislar las dependencias del proyecto:

```bash
python -m venv venv
```

Activar el entorno:

* En **Windows**:

  ```bash
  venv\Scripts\activate
  ```
  
### 2️⃣ Instalar dependencias

```bash
pip install requirements.txt
```

### 3️⃣ Verificar instalación

```bash
pip list
```

Esto mostrará todas las librerías instaladas y sus versiones actuales.

---

## ▶️ Ejecución del proyecto

Ejecutar el script principal:

```bash
python rock-paper-scissors.py
```

El programa abrirá la cámara, detectará las manos y reconocerá los gestos de piedra, papel o tijera utilizando MediaPipe Hands.

---

## 🧩 Compatibilidad y recomendaciones

* Python 3.10 recomendado.
* Evitar usar Python 3.12 o superior, ya que pueden presentarse incompatibilidades en librerias.
