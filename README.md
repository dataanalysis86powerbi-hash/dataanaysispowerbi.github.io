# Predicción de Fuga de Clientes (Telco Customer Churn) 📊
## Proyecto Final - Deep Learning & Redes Neuronales

Este proyecto utiliza una red neuronal profunda (**MLP**) para predecir la probabilidad de que un cliente abandone una compañía de telecomunicaciones, basado en el dataset clásico de **IBM Telco**.

### 🚀 Estructura del Modelo
El modelo está construido con **TensorFlow/Keras** e incluye:
- Capas densas con activación **ReLU**.
- Capas de **Dropout** para evitar el sobreajuste (overfitting).
- Una capa de salida con activación **Sigmoid** para clasificación binaria.
- Preprocesamiento de datos con `StandardScaler` y `LabelEncoder`.

### 🛠️ Tecnologías utilizadas
*   [Python](https://www.python.org)
*   [Google Colab](https://colab.research.google.com) (Entorno de desarrollo)
*   [Pandas](https://pandas.pydata.org) & [NumPy](https://numpy.org) (Manipulación de datos)
*   [Scikit-learn](https://scikit-learn.org) (Preprocesamiento y métricas)
*   [TensorFlow](https://www.tensorflow.org) (Arquitectura de la Red Neuronal)
*   [Matplotlib](https://matplotlib.org) & [Seaborn](https://seaborn.pydata.org) (Visualización)

### 📈 Cómo usar este repositorio
1. El dataset se carga automáticamente desde el enlace **Raw** de GitHub.
2. Puedes ejecutar el notebook directamente en la nube haciendo clic aquí: 
   [![Open In Colab](https://colab.research.google.com)](https://colab.research.google.com/drive/1t6Jmjb7hFBTDTFIDUbwmpLsZKYMN2Oiv)

### 📊 Resultados esperados
El script genera:
- Reporte de clasificación (Precisión, Recall, F1-score).
- Score **ROC-AUC**.
- Gráficas de **Pérdida (Loss)** y **Precisión (Accuracy)** por época.
- Matriz de confusión para evaluar errores de predicción.
