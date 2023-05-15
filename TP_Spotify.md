# Trabajo Práctico Spotify

## Introducción

El objetivo de este trabajo es realizar un análisis exploratorio de un dataset de Spotify. El mismo contiene el historial de reproducciones de un usuario de Spotify durante un año. El dataset se encuentra en el archivo `StreamingHistory.json`.

Para realizar el análisis, se debe utilizar Python y las herramientas vistas en clase. En particular Pandas y Matplotlib. Opcionalmente se pueden utilizar otras herramientas como Seaborn.

Se va a evaluar la calidad del análisis realizado, la presentación de los resultados y la claridad de las conclusiones obtenidas. Ademas se tendrá en cuenta la calidad y prolijidad del código utilizado, se espera que el código esté comentado, que se utilicen nombres de variables descriptivas, y que se definan correctamente las funciones necesarias para realizar el análisis.

## Consigna

El análisis debe incluir al menos los siguientes puntos:

- ¿Que información contiene el dataset? Describir las columnas y los tipos de datos.
- ¿Cuántas canciones se escucharon en total?
- ¿Cuánto tiempo duró el periodo en el que se registraron las reproducciones?
- ¿Cuál es el artista más escuchado?
- ¿Cuál es la canción más escuchada?
- ¿Cuál es el género más escuchado?
- ¿Cuál es el día de la semana en el que más se escucha música?
- ¿En que horario se escucha más música?
- ¿Cuál es el mes en el que más se escucha música?
- ¿Cuál es el artista que más se escucha en cada mes?

Algunas consideraciones a tener en cuenta:

- Al explorar el datasets, se deben "limpiar" los datos antes de visualizar los DataFrames.
- El dataset contiene información de un año. Por lo tanto, se pueden utilizar datos agrupados por mes, día de la semana, etc. Investigar la documentación de Pandas para convertir las fechas al tipo de dato `datetime`.
- Al determinar, por ejemplo, la canción más escuchada, se debe tener en cuenta que una misma canción puede aparecer varias veces en el dataset. Cada registro corresponde a una reproducción de una canción, y contiene un campo `msPlayed` que indica la duración de la reproducción en milisegundos. Por lo tanto, se debe tener en cuenta este campo para determinar la canción más escuchada.
- Para responder a las preguntas, se debe ademas generar visualizaciones que permitan entender mejor los datos. Por ejemplo, se puede generar un gráfico de barras para visualizar el artista más escuchado. Investigar la documentación de Matplotlib para generar distintos tipos de gráficos.

## Entrega

Los resultados deben ser presentados en un notebook de Jupyter. El mismo debe incluir una explicación de los pasos realizados y las conclusiones obtenidas.

Además todas las celdas deben estar ejecutadas y el notebook debe estar guardado con el nombre `spotify_-Apellido1-Apellido2-Apellido3.ipynb`.

## Condiciones de entrega

El notebook debe ejecutarse sin errores y debe incluir:

- El nombre y apellido de los integrantes del grupo.
- Una explicación de los pasos realizados y las conclusiones obtenidas.
- Las visualizaciones generadas.
- El código utilizado para responder a las preguntas y para generar las visualizaciones.

## Fecha de entrega

📅 28 de Mayo a las 23:59 hs.

Se debe entregar en el siguiente [Google Forms]() el Notebook con el análisis realizado.

## Referencias

- [Documentación de Pandas](https://pandas.pydata.org/docs/)
- [Documentación de Matplotlib](https://matplotlib.org/stable/contents.html)
- [Documentación de Python 3](https://docs.python.org/3/)
