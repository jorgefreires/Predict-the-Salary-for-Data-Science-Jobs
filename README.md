# Predict the Salary for Data Science Jobs

Este repositorio contiene el código utilizado para una [competeción de Kaggle](https://www.kaggle.com/competitions/predict-salary-for-data-science-jobs) basada en predecir salarios para trabajos de Data Science. La competición consistia en entrar un modelo de machine learning con unos datos proporcionados, para posteriormente predecir salarios con otros datos tambien propocionados. El repositorio se divide en dos carpetas, notebooks y data, cuyo contenido desgloso a continuación.

## Data
* **salaries_data.csv:** Datos proporcionados para testear y entrenar un modelo de machine learning, los cuales incluyen los salarios.
* **testeo.csv:** Datos proporcionados para realizar la predicción, los cuales no incluyen los salarios.
* **train.csv:** Datos resultantes de la limpieza de salaries_data.csv, con los que finalmente se entreno el modelo.
* **test.csv:** Datos resultantes de la limpieza de testeo.csv, con los que finalmente se realizo la predicción.
* **muestra.csv:** Salarios obtenidos en la predicción.

## Notebooks
* **explore_data.ipynb:** En esta libreta de jupyter se exploraron los datos proporcionados y se realizó la limpieza para el posterior uso de herramientas de machine learning.
* **machine_learning.ipynb:** En esta otra libreta se realizó todo el proceso de machine learning. La primera parte de este proceso consisitio en utilizar pycaret para ver que módelos eran los más adecuados, para posteriomente testear con el uso de grid searching los cinco mejores modelos. Por último se eligio el mejor módelo, se ajustaron más los hiperparámetros y se realizó la predicción.