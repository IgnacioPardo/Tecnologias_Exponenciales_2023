# Trabajo Práctico 1: Modelos Predictivos en SciKit-Learn
## Avanzado Tecnologías Exponenciales 2023

## Consigna

En grupos de 2 o 3 personas, realizar los siguientes ejercicios.

1. Investigar y seleccionar un dataset que cumpla con tener entre 1000 y 10.000 muestras, 5 o más atributos numéricos y al menos un atributo categórico (Recomendación: seleccionar un atributo a predecir binario). De encontrar algún dataset sin atributos categóricos, ¿Como se podría generar uno binario a partir de los atributos numéricos? Se recomienda utilizar Kaggle para la búsqueda del dataset. Antes de avanzar con el trabajo práctico, corroborar el dataset en clase.

2. Realizar un análisis exploratorio de los datos. Se recomienda utilizar gráficos para visualizar la distribución de los datos y la correlación entre los atributos. Se recomienda utilizar la librería `seaborn` para realizar los gráficos.

3. Como resultado del análisis exploratorio, seleccionar un atributo categórico y un atributo numérico para realizar un modelo de clasificación. Se recomienda utilizar la función `LabelEncoder` de SciKit-Learn para convertir el atributo categórico a numérico.

4. Realizar una partición de los datos en conjuntos de entrenamiento y test. La proporción con la cual hacen esta partición es libre. Se recomienda utilizar la función `train_test_split` de SciKit-Learn.

5. Para el atributo numérico a predecir seleccionado:

- Realizar un modelo de regresión lineal utilizando la clase `LinearRegression` de SciKit-Learn.
- Realizar un modelo de Árbol de Decisión utilizando la clase `DecisionTreeRegressor` de SciKit-Learn. Seleccionar hiperparámetros que les parezca mejoren el modelo.

Responder:
¿Que formas tienen de evaluar los resultados de cada árbol de decisión? ¿Como eligen "el mejor árbol"? ¿Como se comparan los resultados de los modelos de regresión lineal y de árbol de decisión?

Sugerencia: Aprovechar los conceptos de validación y de validación cruzada para evaluar los modelos. Pueden utilizar la función `cross_val_score` de SciKit-Learn para evaluar los modelos.

Se recomienda utilizar la función `cross_val_score` de SciKit-Learn para evaluar los modelos.

6. Para el atributo categórico a predecir seleccionado

- Realizar un modelo de clasificación utilizando la clase `LogisticRegression` de SciKit-Learn.
- Realizar un modelo de clasificación utilizando la clase `DecisionTreeClassifier` de SciKit-Learn.

Responder las mismas preguntas que en el punto 5 para este caso.

7. Comparar distintos métodos de validación cruzada. ¿Que ventajas y desventajas tiene cada uno?

8. Escribir una conclusión sobre el trabajo realizado.


## Bonus

- Investigar los métodos GridSearch y RandomSearch para la búsqueda de hiperparámetros. Utilizarlos para encontrar los mejores hiperparámetros para los modelos.

- Para ya sea el atributo categórico como para el numérico, elegir otro modelo de clasificación o regresión que no haya sido utilizado anteriormente. Entrenar el modelo y comparar los resultados con los obtenidos anteriormente.

## Formato de entrega

El trabajo práctico se debe realizar en un notebook de Jupyter. El notebook debe estar subido a un repositorio de GitHub. El link al repositorio debe ser completado en el siguiente [Google Form]().

## Fecha de entrega

El trabajo práctico se debe entregar hasta el 17/09/2023 a las 23:59hs.

## Bibliografía

- [SciKit-Learn](https://scikit-learn.org/stable/)
- [Seaborn](https://seaborn.pydata.org/)
- [Kaggle](https://www.kaggle.com/)
- [Cross Validation](https://scikit-learn.org/stable/modules/cross_validation.html)
