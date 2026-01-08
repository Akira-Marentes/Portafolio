# Portafolio
Proyectos de ciencia de datos donde demuestro mis habilidades de Python, análisis, Machine Learning, etc.

## Organ_Trasplant
### Título
Predicción de éxito en trasplantes de órganos en México usando Machine Learning
### Resumen
Análisis completo del dataset "Trasplante de órganos y tejidos" del Centro Nacional de Trasplantes (CENATRA), además de la construcción de varios modelos de aprendizaje de máquina y aprendizaje profundo con el objetivo de predecir el resultado de cualquier procedimiento de ésta índole con respecto a las variables disponibles (tipo de sangre, relación con el donante, institución, etc), y elegir el mejor modelo en cuánto desempeño y rapidez de aprendizaje.

### Metodología

Limpieza de datos:

- Eliminación y agrupación de categorías
- Tratamiento de valores faltantes
- Codificación de variables categóricas

Exploratory Data Analysis (EDA):

- Análisis univariado y bivariado
- Visualizaciones por institución, órgano y región
- Correlación categórica (Theil’s U)

Modelado:

- Regresión Logística
- Random Forest
- Redes Neuronales

Evaluación:

- ROC-AUC
- Accuracy
- Precision / Recall
- Matriz de confusión
- Análisis de desbalance de clases

### Tecnologías utilizadas

Python:
- Pandas, NumPy
- scikit-learn
- TensorFlow
- Matplotlib, Seaborn

## NVDA_Stock
### Título
Predicción del precio de acciones Nvidia.
### Resumen
Aplicación y comparación de modelos ARIMA, Prophet (Facebook/Meta) y Red Neuronal (LSTM) para la predicción de la serie temporal del precio de cierre de las acciones de la empresa Nvidia.

### Metodología:

Exploratory Data Analysis (EDA):

- Visualización de la serie
- Análisis de tendencia
- Retornos logarítmicos
- Prueba de estacionariedad (ADF)

### Modelos implementados:

- ARIMA (baseline estadístico)
- Prophet (modelo aditivo con regresores)
- LSTM (red neuronal recurrente)

### Evaluación:

División temporal train/test

Métricas:

- MAE
- RMSE
- MAPE

Análisis de residuos y prueba de Ljung-Box

### Tecnologías utilizadas:

Python
- Pandas, NumPy
- statsmodels, pmdarima
- Prophet
- TensorFlow / Keras
- Matplotlib, Seaborn
