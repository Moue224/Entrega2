Introducción a la Ciencia de Datos 2024

Entrega 2 del curso de Introducción a la Ciencia de Datos - Grupo 9

El objetivo de esta segunda entrega es la aplicación de técnicas de reducción de dimensionalidad (PCA) y de técnicas de aprendizaje automático (machine learning) supervisado. Basándonos en  las obras de Shakespeare, dividimos la muestra en un set de datos de entrenamiento y otro de prueba o test; eventualmente útil para aplicar técnicas de predicción. 

La tarea se divide en dos partes: en una primera instancia, aplicamos tareas de limpieza de texto (estudiadas en la primera entrega), transformamos el texto en instancias numéricas aplicando “bag of words” y “tf-itf”, e incluimos análisis de reducción de dimensionalidad con el uso de componentes principales observando la varianza acumulada en cada componente. En la segunda parte, nos centramos en modelos supervisados de clasificación, utilizando el algoritmo Naive Bayes Multinomial, y el modelo Logístico Multinomial. Se evaluó su rendimiento con el set de datos de prueba utilizando la matriz de confusión y las principales métricas con las cuales 
evaluamos la performance.

La base de datos sobre la cual se plantea la tarea es una base de datos relacional, que se estructura en 4 tablas (o data frames) vinculadas entre sí por restricciones de integridad del tipo clave principal-clave foránea. Las tablas son: “paragraphs”, “chapters”, “characters”, y “works”. 

En el jupyter notebook se visualiza la entrega de trabajo ("Segunda_tarea.ipynb")

Luego, aparecen las librerias necesarias ("requirements.txt")

Por último, subimos los datos de las cuatro tablas en la carpeta "data" (los datos están en extensión .csv)

