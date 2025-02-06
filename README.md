# Proyecto de Extracción, Transformación y Modelo de ML con la API de Open Meteo para Monterrey, Nuevo León

Este proyecto consiste en la extracción, transformación y carga (ETL) de datos meteorológicos de la API de Open Meteo para la ciudad de Monterrey, Nuevo León, utilizando Google Colab, AWS Glue, y la creación de un modelo de Machine Learning con `sklearn`. El objetivo es analizar y predecir patrones climáticos basados en los datos históricos obtenidos.

## Tecnologías Utilizadas

- **Google Colab**: Entorno de desarrollo en la nube para la ejecución de notebooks de Python.
- **Pandas**: Librería para la manipulación y análisis de datos.
- **OpenMeteo-Requests**: Librería para interactuar con la API de Open Meteo.
- **Scikit-learn (sklearn)**: Librería para la implementación de modelos de Machine Learning.
- **AWS Glue**: Servicio de ETL en la nube para la transformación y carga de datos.
- **Jupyter Notebook**: Entorno interactivo para la ejecución de código Python.

## Descripción del Proyecto

1. **Extracción de Datos**: Se utiliza la API de Open Meteo para obtener datos meteorológicos históricos de Monterrey, Nuevo León. Los datos incluyen variables como temperatura, humedad, precipitación, velocidad del viento, entre otros.

2. **Transformación de Datos**: Los datos extraídos se transforman utilizando AWS Glue. Durante este proceso, se cambia el esquema de los datos para adaptarlos a las necesidades del modelo de Machine Learning.

3. **Modelo de Machine Learning**: Se implementa un modelo de Machine Learning utilizando `sklearn` para predecir patrones climáticos basados en los datos transformados. El modelo puede ser de regresión, clasificación, o cualquier otro tipo dependiendo del objetivo del análisis.

4. **Visualización y Análisis**: Los resultados del modelo se visualizan y analizan para obtener insights sobre los patrones climáticos de la región.
