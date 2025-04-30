# Análisis de Trastornos del Sueño

Este proyecto tiene como objetivo explorar, entender y modelar datos relacionados con trastornos del sueño, utilizando técnicas de ciencia de datos y aprendizaje automático.

## Archivos principales

### 1. `Trastornos de sueño.ipynb`
Es el archivo principal del proyecto, basado en el trabajo disponible en [Kaggle](https://www.kaggle.com/code/soumyag09/sleep-disorder) de donde ademas se puede descargar la base de datos que se adjunta tambien en este repositorio.

- Contiene el **código base comentado** y **explicado paso a paso**.
- Cada celda incluye una breve **justificación** y, si es necesario, **explicaciones teóricas** para facilitar la comprensión.
- También incluye las **indicaciones necesarias para cargar y ejecutar el modelo** localmente o en Kaggle.

### 2. `Reporte.pdf`
Una vez revisado el notebook, se recomienda consultar este archivo. Contiene:

-  **Marco teórico** sobre los trastornos del sueño.
-  **Descripción de la metodología** aplicada.
- Presentación de los **resultados más relevantes** obtenidos con el modelo.

### 3. `Complemento_trabajo_original.ipynb`
Este archivo incluye un análisis adicional del modelo implementado con árboles de decisión:

- Evaluación **individualizada** del modelo.
- Pruebas de hipótesis estadísticas aplicadas.
- Todo lo necesario para replicar el análisis ya está **importado y configurado**.
- Al final se encuentra una sección de **gráficas** que contiene todas las figuras mostradas en el PDF, junto con una serie de páginas consultadas para la implementación del modelo de machine learning `DecisionTreeClassifier`.

## Requisitos

Para ejecutar los notebooks necesitas tener instalado:

- Python 
- Jupyter Notebook o Google Colab
- Bibliotecas: Importar las librerías ya especificadas en las celdas.

## Referencias

- Soumya Ghosh. (2022). *Sleep Disorder Detection using Machine Learning*. Kaggle. https://www.kaggle.com/code/soumyag09/sleep-disorder
- Dataset original: https://www.kaggle.com/datasets/sid321axn/sleep-disorder-dataset
- Documentación de scikit-learn: https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html
