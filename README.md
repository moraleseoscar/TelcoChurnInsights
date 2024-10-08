# Anaemia-Prediction-EDA

## Descripción

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) para predecir la anemia utilizando datos de píxeles de imágenes y niveles de hemoglobina utilizando dos modelos distintos de Machine Learning. El análisis está contenido en un Jupyter Notebook (`Anaemia.ipynb`), y el conjunto de datos se encuentra en `dataset/anaemia.csv`.

## Estructura del Proyecto

- **Anaemia.ipynb**: Notebook que contiene el análisis exploratorio de datos, incluyendo visualizaciones, manejo de datos faltantes, análisis estadísticos, y la identificación de correlaciones clave.
- **dataset/anaemia.csv**: Archivo CSV que contiene el conjunto de datos utilizado en el análisis. Este dataset incluye variables como sexo, porcentajes de píxeles rojos, verdes y azules, niveles de hemoglobina, y si la persona es anémica o no.

## Objetivo

El objetivo de este proyecto es preparar y explorar los datos para utilizarlos en la construcción de dos modelos de machine learning que puedan predecir la variable respuesta: anemia. Este análisis exploratorio permitirá identificar patrones y relaciones importantes en los datos que servirán para mejorar la precisión y la interpretación de los modelos predictivos.

## Contenido del Notebook

1. **Carga y Visualización de Datos**: Se realiza una primera inspección de los datos para entender su estructura y contenido.

2. **Limpieza de Datos**: Procesamiento de datos faltantes y corrección de valores atípicos o inconsistentes.

3. **Análisis Descriptivo**: Estadísticas descriptivas de las principales variables del dataset.

4. **Visualización de Datos**: Gráficos y diagramas que ayudan a entender la distribución de las variables y sus posibles relaciones.

5. **Análisis de Correlación**: Evaluación de las correlaciones entre variables numéricas para identificar posibles predictores de la anemia.

6. **Preparación para Modelado**: Generación de insights y preparación de los datos para el entrenamiento de modelos de machine learning.

## Conclusión de los valores SHAP y los modelos
Tanto el modelo Random Forest y SVM lograron generalizar el conjunto de datos aceptablemente. Se utilizó la herramienta de análisis SHAP para identificar las variables más importantes en la predicción de la anemia. Se encontró que los niveles de hemoglobina y los porcentajes de píxeles rojos y verdes son las variables más influyentes en la predicción de la anemia; por otro lado, la variable sexo no resultó ser significativa en la predicción de la anemia, lo que sugiere que otros factores pueden ser más relevantes en la detección de esta condición. Estos resultados pueden ser útiles para futuras investigaciones y para mejorar la precisión de los modelos predictivos. 

## Cómo Ejecutar el Proyecto

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tuusuario/Anaemia-Prediction-EDA.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd Anaemia-Prediction-EDA
   ```

3. Asegúrate de tener las dependencias necesarias instaladas, y abre el Jupyter Notebook:
   ```bash
   jupyter notebook Anaemia.ipynb
   ```

---

Este README te servirá para explicar claramente la estructura y propósito del proyecto a otros colaboradores o para ti mismo en el futuro. ¿Hay algo más que te gustaría agregar?
