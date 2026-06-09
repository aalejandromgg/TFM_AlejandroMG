# TFM_AlejandroMG

Repositorio que contiene el código desarrollado para el Trabajo Fin de Máster (TFM) de **Alejandro Muñoz García**, titulado:

**"Detección de anomalías en redes de telecomunicaciones mediante Análisis de Datos Funcionales y Aprendizaje Automático"**

## Estructura del repositorio

A continuación, se describen los principales cuadernos y archivos utilizados durante el desarrollo del trabajo:

### 3_3DatosFuncionales.ipynb
Cuaderno dedicado al análisis funcional de series temporales. En él se aplican bases de **Fourier** y **B-Splines** para representar las observaciones, comparar ambas aproximaciones y estudiar el número óptimo de bases necesarias para una representación adecuada de los datos.

### 3_4_1ClusterizacionSemanas.ipynb
Archivo orientado a la caracterización y agrupación de semanas según su comportamiento. Incluye:

- Identificación de distintos tipos de semanas dentro de una institución.
- Clasificación de diferentes tipos de instituciones.
- Detección de anomalías mediante técnicas basadas en umbrales.

### 3_4_2ClusterizacionSemanas.ipynb
Cuaderno en el que se aplica **Functional Principal Component Analysis (FPCA)** para identificar los patrones de comportamiento más representativos de las semanas y de las instituciones a partir de sus componentes principales.

### 3_4_3Correlacion.ipynb y 3_4_3Covarianza.ipynb
Archivos centrados en el análisis multivariante de los datos. Se estudian las relaciones entre variables mediante matrices de correlación y covarianza, identificando los pares con mayor dependencia y analizando posibles comportamientos anómalos asociados.

### 3_5_X.ipynb
Conjunto de cuadernos destinados al diseño, entrenamiento y evaluación de los modelos predictivos. Incluyen:

- Definición de la arquitectura de los modelos.
- Entrenamiento y validación de los modelos.
- Reconstrucción y visualización de las predicciones.
- Evaluación mediante métricas de rendimiento.

### 4_2_X.ipynb
Cuadernos dedicados a la comparación del rendimiento de redes **LSTM** bajo los diferentes niveles de agregación de los datos.

## Autor

**Alejandro Muñoz García**

Trabajo Fin de Máster (TFM)  
Máster en Ingeniería de Telecomunicación (EUR-ACE®)
Año de realización: 2026
