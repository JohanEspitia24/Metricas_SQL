# Proyecto: Modelado Predictivo para Enfermedades Cardíacas y Eventos Vasculares

Este repositorio alberga dos notebooks enfocados en el análisis integral y modelado predictivo de datos médicos relacionados con enfermedades cardíacas y accidentes cerebrovasculares. La combinación de procesamiento con PySpark y técnicas clásicas de machine learning permite abordar desde grandes volúmenes de datos hasta evaluaciones precisas de modelos.

## Descripción de los notebooks

### 1. `Johan_Espitia_PySpark_Taller_Metricas.ipynb`

Este notebook se orienta a la manipulación y exploración de datos a gran escala utilizando PySpark. Las actividades clave incluyen:

- Importación y carga de datos remotos en formato CSV.  
- Identificación y tratamiento de datos faltantes o inconsistentes para asegurar calidad.  
- Exploración detallada mediante análisis estadístico y visualizaciones, como mapas de calor de correlaciones, para revelar relaciones importantes entre variables.  
- Reflexión sobre las características más influyentes para la construcción de modelos predictivos.

**Objetivo principal:** Desarrollar habilidades para trabajar con datos masivos y preparar la base para el desarrollo de modelos de predicción en entornos Big Data.

---

### 2. `Johan_Espitia_Stroke_Metricas.ipynb`

Este notebook está dedicado al desarrollo y evaluación de un modelo supervisado para la predicción de eventos cardiovasculares graves:

- Preprocesamiento avanzado, que incluye la imputación de valores faltantes y la transformación de variables categóricas para el entrenamiento.  
- Construcción de un modelo basado en árboles de decisión con control de profundidad para evitar sobreajuste.  
- Análisis detallado del rendimiento del modelo a través de:  
  - Matriz de confusión para comprender errores y aciertos.  
  - Métricas clave:  
    - **Exactitud (Accuracy):** 94.71%  
    - **Sensibilidad (Recall):** 2.50%  
    - **Precisión (Precision):** 50.00%  
    - **AUC (Área Bajo la Curva ROC):** 77%  
  - Visualización gráfica de la curva ROC para evaluar la discriminación del modelo.

**Conclusión:** El modelo identifica bien a los pacientes sin eventos (alta exactitud y especificidad), pero presenta dificultades para detectar correctamente a los afectados (baja sensibilidad). Se recomiendan ajustes en el balance de datos y la exploración de otros modelos para mejorar la detección.

---

## Requisitos del entorno

Para ejecutar estos notebooks se recomienda tener instalado:

- Python 3.7 o superior.  
- Librerías necesarias:  
  - `pyspark`  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`

