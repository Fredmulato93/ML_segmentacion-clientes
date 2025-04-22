# Proyecto de Segmentación de Clientes con K-Means (Machine Learning)

## 🌐 Descripción del Proyecto
Este proyecto tiene como objetivo segmentar una base de clientes de una institución financiera utilizando el algoritmo de **clustering no supervisado K-Means**. Mediante este análisis, se pretende descubrir grupos de clientes con características financieras similares que permitan personalizar estrategias comerciales, mejorar la oferta de productos y optimizar la gestión del riesgo.

## 📅 Dataset Utilizado
El dataset se titula `Model_creditoPersonal.csv` y contiene información de 5000 clientes, incluyendo variables como:
- Edad
- Experiencia laboral
- Ingreso mensual
- Tamaño del grupo familiar
- Nivel educativo
- Hipoteca
- Uso de tarjetas de crédito
- Acceso a cuentas financieras y canales digitales

Se ha incluido una muestra del dataset (500 registros) en la carpeta `/src/data_sample` bajo el nombre `Model_creditoPersonal_sample.csv`, cumpliendo el límite de 5MB para fines de entrega.

## 🤖 Solución Adoptada
Se ha utilizado el algoritmo **K-Means**, aplicando previamente una etapa de preprocesamiento que incluye:
- Selección de variables relevantes.
- Escalado estándar de las variables.
- Determinación del número óptimo de clusters mediante el método del codo.

El modelo final segmenta a los clientes en **3 grupos** distintos que representan diferentes perfiles financieros. Los resultados fueron visualizados mediante scatter plots y boxplots.

## 📁 Estructura del Repositorio# ML_segmentacion-clientes
ML_segmentacion-clientes/ ├── README.md ├── src/ │ ├── data_sample/ │ │ └── Model_creditoPersonal_sample.csv │ ├── img/ │ │ ├── grafico_elbow.png │ │ └── scatter_income_ccavg.png │ ├── notebooks/ │ │ └── pruebas_kmeans.ipynb │ ├── results_notebook/ │ │ └── kmeans_segmentation_final.ipynb │ ├── models/ │ │ └── modelo_kmeans.pkl │ └── utils/ │ ├── preprocesamiento.py │ └── funciones_clustering.py

## 🔐 Requisitos de Ejecución
Instalar las siguientes librerías (puedes usar un entorno virtual):
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## 🚀 Cómo Ejecutar
1. Clonar el repositorio.
2. Asegurarse de tener el archivo CSV en la carpeta `data_sample`.
3. Ejecutar el notebook `kmeans_segmentation_final.ipynb` ubicado en `src/results_notebook`.

## 👩‍💼 Autor
Este proyecto ha sido desarrollado como parte de una entrega de aprendizaje automático, integrando conocimientos de ciencia de datos, preprocesamiento y visualización.
