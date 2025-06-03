# 🖼️ Clasificación de Imágenes con CNN (Keras & TensorFlow)

Este repositorio contiene un proyecto de clasificación de imágenes utilizando una **Red Neuronal Convolucional (CNN)** construida con Keras y TensorFlow. El modelo clasifica imágenes en base a características visuales, aplicando técnicas comunes de aprendizaje profundo y estrategias de preprocesamiento de imágenes.

---

## 📁 Estructura del Proyecto

```
📦 Clasificacion-Imagenes-CNN/
├── explore (2).ipynb         # Notebook con entrenamiento y evaluación del modelo
├── README.md                 # Descripción general del proyecto e instrucciones
├── data/                     # Carpeta con las imágenes de entrenamiento y prueba
```

---

## 🖼️ Preprocesamiento de Imágenes

- Tamaño: 128x128 RGB
- Aumento de datos con `ImageDataGenerator`
- División con `train_test_split`

---

## 🧠 Arquitectura del Modelo

Construido con la API `Sequential` de Keras:
- 👁️ Capas `Conv2D` y `MaxPooling2D`
- 🚿 Regularización con `Dropout`
- 🔁 Normalización con `BatchNormalization`
- 🧠 Capas densas con funciones de activación
- 🛑 Callbacks: `EarlyStopping` y `ReduceLROnPlateau` para optimización del entrenamiento

---

## 🧪 Cómo Ejecutar

### Requisitos

```bash
pip install tensorflow keras matplotlib numpy pandas scikit-learn
```

### Ejecutar el notebook

```bash
jupyter notebook "explore (2).ipynb"
```

Asegúrese de que la carpeta `data/` contenga subcarpetas estructuradas por clase de imagen.

---

## 📚 Librerías Utilizadas

- `tensorflow`, `keras`
- `numpy`, `pandas`
- `matplotlib`
- `sklearn`

---

## 🚀 Objetivos del Proyecto

- Clasificar imágenes con técnicas de aprendizaje profundo
- Demostrar la construcción y entrenamiento de una arquitectura CNN
- Visualizar el progreso de entrenamiento y resultados de predicción

---

## 📬 Contacto

Desarrollado como parte de una exploración en visión por computadora. ¡Se agradecen forks y contribuciones!
