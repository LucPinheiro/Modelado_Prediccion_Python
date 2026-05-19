Modelado de Regresión y Clasificación con Spotify Tracks

En esta tarea se trabajó con el dataset `spotify_tracks.csv` utilizando diferentes técnicas de Machine Learning para analizar y predecir información relacionada con canciones de Spotify.

El proyecto se desarrolló en el notebook:

- `401.ipynb`

## Objetivos de la práctica

Durante la tarea se realizaron diferentes procesos de análisis y modelado:

- Exploración y limpieza del dataset
- Separación de variables predictoras y variables objetivo
- Normalización y preparación de datos
- Análisis descriptivo y correlaciones
- Modelado de regresión para predecir la popularidad de canciones
- Modelado de clasificación para predecir géneros musicales
- Comparación de modelos mediante métricas y validación cruzada
- Visualización de resultados utilizando Matplotlib

## Modelos utilizados

### Regresión
- Regresión Lineal Simple
- Regresión Lineal Múltiple
- Random Forest Regressor

### Clasificación
- Support Vector Machine (SVM)
- Random Forest Classifier

## Librerías utilizadas

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Dataset

El dataset utilizado contiene más de 114.000 registros de canciones de Spotify con información relacionada con:

- popularidad
- energía
- danceability
- loudness
- tempo
- acousticness
- valence
- géneros musicales
- entre otras características

## Observaciones

Durante la realización de la práctica surgieron algunas dificultades relacionadas con el tamaño del dataset y el tiempo de entrenamiento de algunos modelos, especialmente SVM y Random Forest.

Para mejorar la visualización y comprensión de los resultados también se utilizaron gráficos realizados con Matplotlib.

## Estructura del proyecto

```bash
├── 401.ipynb
├── spotify_tracks.csv
└── README.md

