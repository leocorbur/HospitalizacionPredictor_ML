# **Hospitalización Predictor: Análisis y Modelamiento**

Este repositorio presenta un análisis completo y un modelo de predicción de hospitalización para pacientes. A continuación se detalla el proceso de análisis exploratorio de datos y modelamiento utilizando un clasificador de árbol de decisión.

## 1. Procesamiento

Primero, se realiza una carga y limpieza de datos desde el archivo 'BBDD_Hospitalización.xlsx'. Las operaciones incluyen:

- Eliminación de filas con valores nulos.
- Eliminación de outliers en las columnas numéricas.
- Conversión de tipos de datos para las columnas categóricas.
- Eliminación de filas que contienen ceros en todas sus columnas.
- Selección de un subconjunto de columnas relevantes para el análisis de correlación y predicción.

###  Análisis Exploratorio de Datos

Se explora la distribución de variables, relaciones entre ellas y correlaciones. Se visualizan gráficamente las relaciones y se evalúa la importancia de las variables en la clasificación.

## 2. Modelamiento

En esta fase, nos enfocamos en el modelamiento del conjunto de datos previamente preparado. El objetivo principal es clasificar a un paciente como hospitalizado o no hospitalizado. Utilizaremos un conjunto de variables relacionadas con los antecedentes del paciente, morbilidad y complicaciones infecciosas.

### Preparación para el Modelamiento

Separamos el conjunto de datos en variables predictoras (X) y la variable objetivo (y). Luego, dividimos el conjunto de datos en conjuntos de entrenamiento y prueba para poder evaluar el rendimiento del modelo.

### Modelamiento con Árbol de Decisión

Utilizamos un clasificador de árbol de decisión para realizar la clasificación. Ajustamos el modelo y realizamos predicciones tanto en el conjunto de entrenamiento como en el conjunto de prueba.

### Evaluación del Modelo

Evaluamos el rendimiento del modelo utilizando varias métricas, incluyendo la precisión (accuracy) y el F1-score. Además, visualizamos la matriz de confusión para evaluar la calidad de las predicciones.

### Importancia de Variables

Exploramos la importancia de las variables en el proceso de clasificación. Esto nos ayuda a entender qué características son más relevantes para predecir la hospitalización.

### Optimización de Hiperparámetros

Finalmente, exploramos la optimización de los hiperparámetros del modelo utilizando una búsqueda en cuadrícula (Grid Search). Esto nos permite encontrar los mejores parámetros para mejorar el rendimiento del modelo.

Este modelo de árbol de decisión proporciona una base sólida para la clasificación de pacientes en categorías de hospitalización. La optimización de hiperparámetros permite mejorar el rendimiento del modelo, proporcionando resultados más precisos y confiables. Este modelo puede ser el punto de partida para investigaciones posteriores y aplicaciones clínicas. Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto a leocorbur@gmail.com. ¡Gracias por revisar este proyecto!
