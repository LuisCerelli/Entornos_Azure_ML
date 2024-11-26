# Diabetes Prediction Model using Logistic Regression and AzureML
### <u>Nota: Obtenido de **Learn Microsoft**</u>

Este proyecto utiliza un modelo de **regresión logística** para predecir la diabetes basado en un conjunto de datos. El modelo se entrena utilizando Azure Machine Learning y los resultados se visualizan a través de las métricas de rendimiento como **accuracy** y **AUC**. Además, el proyecto pone énfasis en el uso de **AzureML** para la creación y administración de experimentos en la nube.

## Descripción del Proyecto

El objetivo de este proyecto es utilizar un conjunto de datos sobre diabetes para entrenar un modelo de regresión logística y evaluar su rendimiento. Se ha utilizado **AzureML** para configurar y ejecutar los trabajos de machine learning en un entorno controlado. Las métricas generadas son almacenadas en el sistema de Azure y se monitorean a través de la interfaz de usuario.

### Características Principales:

- **Preprocesamiento de datos**: Carga del conjunto de datos y separación de características y etiquetas.
- **Entrenamiento del modelo**: Se utiliza **regresión logística** para entrenar el modelo de predicción de diabetes.
- **Evaluación del modelo**: Se calculan métricas como **accuracy** y **AUC** para evaluar la efectividad del modelo.
- **Integración con AzureML**: El modelo se entrena en la nube, utilizando **AzureML** para gestionar entornos, ejecutarse en clústeres y monitorizar los trabajos.

## Estructura del Repositorio

- `diabetes.csv`: Conjunto de datos utilizado para entrenar el modelo.
- `diabetes-training.py`: Script de Python que carga el conjunto de datos, entrena el modelo y calcula las métricas de rendimiento.
- `README.md`: Documento que describe el proyecto y cómo utilizarlo.

## Requisitos

Para ejecutar este proyecto localmente, asegúrate de tener los siguientes paquetes instalados:

- `pandas`
- `numpy`
- `scikit-learn`
- `azure-ai-ml`
- `azure-identity`

Puedes instalar los requisitos utilizando pip:

```bash
pip install pandas numpy scikit-learn azure-ai-ml azure-identity
```

### Requisitos adicionales para AzureML

Este proyecto depende de **Azure Machine Learning**, por lo que necesitarás una cuenta en Azure y configurar tu entorno para usar **AzureML SDK**.

## Uso

Para ejecutar el script localmente, asegúrate de tener el archivo `diabetes.csv` en el mismo directorio que el script, y luego ejecuta el siguiente comando:

```bash
python diabetes-training.py
```

Este script entrenará el modelo utilizando los datos proporcionados y mostrará los resultados de las métricas en la consola.

### Integración con AzureML

Si deseas entrenar el modelo en **AzureML**, configura y envía el trabajo de entrenamiento usando los métodos proporcionados en el script. El trabajo se ejecutará en un **clúster de AzureML** y podrás monitorear el progreso a través de la URL proporcionada por AzureML.

## Resultados y Métricas

El modelo calcula las siguientes métricas de rendimiento:

- **Accuracy**: La precisión del modelo, es decir, la proporción de predicciones correctas.
- **AUC (Area Under the Curve)**: El área bajo la curva ROC, que mide la capacidad del modelo para distinguir entre las clases positivas y negativas.

### Métricas Registradas en AzureML

En este proyecto, se registran las métricas de **accuracy** y **AUC** en AzureML, lo que te permite visualizar el rendimiento del modelo a lo largo del tiempo y comparar diferentes ejecuciones.

## Compromiso con el Aprendizaje Continuo

Este proyecto es parte de un esfuerzo continuo por mejorar habilidades en el campo de **Data Science** y **Machine Learning**. Mi enfoque está en **aprender de manera constante**, dominando herramientas como **AzureML** y adquiriendo nuevas competencias en **procesamiento de datos**, **modelado predictivo** y **evaluación de resultados**. 

La **búsqueda constante de conocimiento** y la **mejora continua** son principios clave, para mi, fundamentales para adaptarse a los cambios en el campo y ofrecer soluciones innovadoras y efectivas.

