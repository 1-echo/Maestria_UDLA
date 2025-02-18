# Tesis: Pronóstico del sector eléctrico en Ecuador: evolución mensual por tipo de fuente desde 2013 hasta 2023.

## Nombre de la Maestría:
Maestría en Inteligencia de Negocios y Ciencia de Datos

## Universidad:
Universidad de las Américas

## Nombre de los Integrantes:
- Claudio Arias

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo predictivo para el sector eléctrico en Ecuador, analizando la generación eléctrica mensual por tipo de fuente entre 2013 y 2023. Los modelos de predicción SARIMA y Prophet fueron utilizados para generar pronósticos de alta precisión, basados en datos de la Agencia de Regulación y Control de Electricidad, y evaluados mediante métricas como RMSE y MAPE. Los resultados permiten evaluar el comportamiento del sector y proponer mejoras en la planificación energética.

### Problema a Resolver:
La creciente demanda energética en Ecuador plantea la necesidad de contar con modelos predictivos precisos para la planificación y la toma de decisiones. Este proyecto busca resolver la incertidumbre en la disponibilidad de energía mediante modelos estadísticos, permitiendo anticipar la oferta y reducir la dependencia de fuentes externas.

### Modelo Seleccionado:
1. **SARIMA** - Modelo autorregresivo estacional, adecuado para series temporales con estacionalidad.
2. **Prophet** - Modelo de descomposición que facilita el análisis de estacionalidad y tendencias, con capacidad de ajuste de hiperparámetros para mejorar la precisión.

### Base de Datos:
La base de datos fue obtenida de la Agencia de Regulación y Control de Electricidad en Ecuador (SISDAT), con registros de generación eléctrica mensual para cada tipo de fuente desde 2013 hasta 2023.

## Estructura del Repositorio

- **data/**: Contiene los archivos de datos utilizados en el análisis. Estos archivos incluyen información sobre la generación eléctrica por tipo de fuente desde 2013 hasta 2023.

- **visualizaciones/**: Esta carpeta contiene las gráficas generadas a partir del análisis de los datos. Las visualizaciones son fundamentales para comprender las tendencias y patrones en la generación eléctrica.

- **analisis_de_datos.ipynb**: Archivo Jupyter Notebook que documenta el desarrollo de la tesis, incluyendo la implementación de los modelos SARIMA y Prophet, así como el análisis de resultados, el archivo se encuentra comprimido debido a las limitaciones de espacio en Github.

- **documento_tesis.pdf**: El documento final de la tesis en formato PDF. Este archivo presenta de manera detallada la metodología, resultados y conclusiones del estudio.

- **README.md**: Instrucciones y descripción general del proyecto.
  
- **requirements.txt**: Archivo con los paquetes necesarios para ejecutar el notebook.

### Cómo Usar el Notebook para Replicar los Resultados

1. **Instalación de dependencias**:
   - Asegúrate de tener `Python 3.x` instalado.
   - Instala las dependencias requeridas ejecutando:
     ```bash
     pip install -r requirements.txt
     ```

2. **Ejecutar el Notebook**:
   - Abre el archivo `data_analysis.ipynb` en un entorno Jupyter Notebook o Google Colab.
   - Ejecuta cada celda en el orden indicado para reproducir el análisis y los resultados.

3. **Notas adicionales**:
   - Para obtener los resultados de predicción, asegúrate de que los archivos de datos se encuentran en la carpeta `/data` y que el entorno tiene permisos para acceder a esta carpeta.

