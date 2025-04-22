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


## 🚀 Cómo Ejecutar
1. Clonar el repositorio.
2. Asegurarse de tener el archivo CSV en la carpeta `data_sample`.
3. Ejecutar el notebook `kmeans_segmentation_final.ipynb` ubicado en `src/results_notebook`.

## Autor: Fred Alberto Mulato Alfaro
Este proyecto ha sido desarrollado como parte de una entrega de aprendizaje automático, integrando conocimientos de ciencia de datos, preprocesamiento y visualización.

## 🔐 Requisitos de Ejecución
Instalar las siguientes librerías (puedes usar un entorno virtual):
- pip install pandas numpy matplotlib seaborn scikit-learn


# Customer Segmentation Project with K-Means (Machine Learning)

## 🌐 Project Description
The goal of this project is to segment a customer base from a financial institution using the **unsupervised clustering algorithm K-Means**. This analysis aims to uncover groups of customers with similar financial characteristics to enable tailored marketing strategies, improve product offerings, and optimize risk management.

## 📅 Dataset Used
The dataset is titled `Model_creditoPersonal.csv` and contains information about 5,000 customers, including variables such as:
- Age
- Work experience
- Monthly income
- Family size
- Education level
- Mortgage
- Credit card usage
- Access to financial products and digital channels

A sample of the dataset (500 records) has been included in the `/src/data_sample` folder under the name `Model_creditoPersonal_sample.csv`, complying with the 5MB submission size limit.

## 🤖 Adopted Solution
The chosen method is the **K-Means algorithm**, applied after a preprocessing stage that includes:
- Selection of relevant variables.
- Standard scaling of the data.
- Determination of the optimal number of clusters using the elbow method.

The final model segments customers into **3 distinct groups**, representing different financial profiles. The results were visualized using scatter plots and boxplots.

## 📁 Repository Structure

ML_segmentacion-clientes/ ├── README.md ├── README_en.md ├── src/ │ ├── data_sample/ │ │ └── Model_creditoPersonal_sample.csv │ ├── img/ │ │ ├── grafico_elbow.png │ │ └── scatter_income_ccavg.png │ ├── notebooks/ │ │ └── pruebas_kmeans.ipynb │ ├── results_notebook/ │ │ └── kmeans_segmentation_final.ipynb │ ├── models/ │ │ └── modelo_kmeans.pkl │ └── utils/ │ ├── preprocesamiento.py │ └── funciones_clustering.py

## 🚀 How to Run
1. Clone the repository.
2. Ensure the CSV file is located in the `data_sample` folder.
3. Run the notebook `kmeans_segmentation_final.ipynb` located in `src/results_notebook`.

## 👩‍💼 Author
This project was developed as part of a machine learning assignment, integrating data science, preprocessing, and visualization techniques.

## 🔐 Requirements
Install the following libraries (use a virtual environment if needed):
```bash
pip install pandas numpy matplotlib seaborn scikit-learn


