# 💳 Predictor de Morosidad: Deep Learning para Gestión de Riesgo Bancario

Este repositorio contiene el proyecto final de la Especialización en Inteligencia Artificial desarrollado por **Darcy Andrés Torvisco Andrade**.

## 🎯 Objetivo del Proyecto
Desarrollar un modelo de **Redes Neuronales Profundas (DNN)** capaz de predecir la probabilidad de incumplimiento de pago de clientes. El fin es permitir que el equipo de recaudaciones priorice las gestiones de cobranza preventiva en campo.

## 🚀 Resultados Clave
* **Accuracy Final:** 80% en el conjunto de prueba.
* **Recall de Mora:** Se logró identificar correctamente al **51.3% de los deudores reales** (674 casos), optimizando el uso de recursos operativos.
* **Técnica de Balanceo:** Se utilizó **SMOTE** para manejar el desbalance de clases de 14.77:1 presente en los datos originales.

## 🛠️ Tecnologías y Metodología
* **Lenguaje:** Python (Google Colab).
* **Frameworks:** TensorFlow / Keras para el modelo de Deep Learning.
* **Preprocesamiento:** Escalado de datos y balanceo sintético.
* **Arquitectura:** Red neuronal secuencial con capas densas (64-32-16) y regularización mediante **Dropout (0.2)** y **EarlyStopping**.

## 📁 Estructura del Repositorio
* `notebooks/`: Contiene el notebook ejecutable `final_project.ipynb`.
* `figures/`: Gráficas de rendimiento, Matriz de Confusión y Curva ROC.
* `data/`: Información sobre el dataset utilizado (UCI Machine Learning Repository).* Usen GitHub como portafolio académico
* Integren experimentación, evaluación y visualización en un único flujo reproducible
