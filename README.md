# Predicción de precios inmobiliarios con Properati (Argentina)

En este proyecto construyo un modelo de machine learning para **predecir precios de propiedades** en Argentina a partir del dataset de Properati.  
Además de entrenar y comparar distintos modelos, dejo todos los datos y resultados guardados en **MongoDB Atlas**.

---

## 1. Objetivo

- Limpiar y explorar el dataset de Properati (Argentina).
- Preparar un **dataset limpio y preprocesado** apto para ML.
- Entrenar y comparar al menos **dos modelos de regresión**:
  - `RandomForestRegressor`
  - `GradientBoostingRegressor`
- Evaluar con métricas:
  - **MAE**, **RMSE** y **R²**.
- Seleccionar un modelo final y analizar su desempeño.
- Guardar en una base de datos NoSQL (MongoDB Atlas):
  - **Datos de entrada** (dataset limpio).
  - **Resultados del modelo** (métricas y predicciones).
  - **Configuración / parametrización del modelo** seleccionado.

---

## 2. Dataset

Fuente: Kaggle – alejandroczernikier/properati-argentina-dataset

Accedo al dataset usando la librería kagglehub con el adaptador KaggleDatasetAdapter.PANDAS.

Archivo principal utilizado: entrenamiento.csv.

Si abrís el proyecto en Google Colab, el entorno ya está preparado para usar kagglehub, por lo que solo tenés que ejecutar las celdas para descargar y cargar el dataset automáticamente.
