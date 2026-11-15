# Análisis de la Deserción Escolar en Bolivia – EH2025

## Proyecto académico de posgrado

**Caso 1:** Análisis de la Deserción Escolar en Bolivia  
**Fuente de datos:** Encuesta de Hogares 2025 – Instituto Nacional de Estadística de Bolivia (INE).

## 1. Descripción del proyecto

El proyecto analiza los factores sociodemográficos, económicos y geográficos relacionados con la inasistencia escolar de la población de 6 a 19 años en Bolivia, utilizando microdatos de la Encuesta de Hogares 2025.

Se aplican técnicas de análisis exploratorio, procesamiento de datos, visualización interactiva, clustering y aprendizaje automático para identificar perfiles de riesgo educativo.

**Nota metodológica:** la variable estudiada representa inasistencia o falta de matriculación en el periodo de referencia. No debe interpretarse automáticamente como abandono escolar definitivo.

## 2. Objetivo general

Identificar los factores asociados a la inasistencia escolar en Bolivia mediante técnicas de analítica de datos y modelos de Machine Learning, con el propósito de generar evidencia que contribuya a la formulación de políticas públicas educativas.

## 3. Estructura del repositorio

```text
Proyecto_EH2025_ML_Caso1/
├── data/
├── notebooks/
├── src/
├── outputs/
├── docs/
├── .gitignore
├── requirements.txt
└── README.md
```

Los microdatos originales y las bases de datos privadas se mantienen fuera del repositorio público.

## 4. Tecnologías utilizadas

- Python
- Google Colab
- DuckDB
- Pandas y NumPy
- Scikit-learn
- XGBoost
- Plotly
- Folium
- YData-Profiling
- SHAP

## 5. Metodología

1. Ingesta y validación de microdatos EH2025.
2. Integración y procesamiento mediante DuckDB.
3. Análisis exploratorio de datos.
4. Construcción de indicadores de asistencia e inasistencia escolar.
5. Visualización de patrones geográficos y sociodemográficos.
6. Segmentación mediante técnicas de clustering.
7. Entrenamiento y evaluación de modelos predictivos.
8. Interpretación de resultados y elaboración de recomendaciones.

## 6. Población de estudio

La población analítica está constituida por personas de 6 a 19 años, seleccionadas de la Encuesta de Hogares 2025, conforme a los criterios de inclusión y depuración documentados en los notebooks.

## 7. Ejecución

El procesamiento se realiza en Google Colab.

Para preparar el entorno:

```bash
pip install -r requirements.txt
```

Los microdatos deben estar disponibles en un espacio privado y no deben incorporarse al repositorio público.

## 8. Resultados

En esta sección se incorporarán los resultados finales de:

- Análisis exploratorio.
- Visualizaciones interactivas.
- Segmentación de perfiles educativos.
- Comparación de modelos predictivos.
- Interpretabilidad de variables.
- Recomendaciones de políticas públicas.

## 9. Consideraciones sobre los datos

Los resultados se interpretan considerando las características de la muestra, los factores de expansión y las limitaciones de la encuesta. Las asociaciones identificadas por los modelos no representan necesariamente relaciones causales.

## 10. Fuente de información

Instituto Nacional de Estadística de Bolivia (INE). Encuesta de Hogares 2025.

Catálogo ANDA: http://anda.ine.gob.bo/index.php/catalog/256
