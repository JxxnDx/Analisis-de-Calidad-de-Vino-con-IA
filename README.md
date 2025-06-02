# Análisis de la Calidad de Vino Blanco con IA

![BannerIA](https://github.com/user-attachments/assets/fe1eb49f-834b-4466-a65d-0aee8f999542)

## Autores
Daniel Badillo - 2220071, Juan David Pallares - 2220079

Escuela Ingeniería de Sistemas - Universidad Industrial de Santander.

## Dataset
El dataset White Wine Quality contiene información sobre características de distintas variantes de vino blanco, que está evaluado con una variable "Quality" discreta de 0 a 10. 

Contiene 4898 registros y 12 columnas distintas, todas numéricas.

[White Wine Quality](https://www.kaggle.com/datasets/piyushagni5/white-wine-quality/data)

## Modelos
- GaussianNB
- RandomForest
- SVC
- Deep Neural Network
- KMeans (k=2, k=3, PCA, TSNE)
- DBSCan (PCA, TSNE)

## Enlaces
- [Código](https://colab.research.google.com/drive/1KaCnuniFLZtTSVGKjOyMbGoZFbn6lSYZ?usp=sharing)

## Motivación
La inteligencia artificial se ha convertido en una herramienta clave para resolver problemas en distintas áreas, permitiendo analizar grandes cantidades de datos y encontrar patrones que de otra manera serían difíciles de detectar. Dentro de este campo, el Machine Learning (ML) y el Deep Learning (DL) ofrecen enfoques que, aunque diferentes, buscan alcanzar el mismo objetivo: realizar predicciones que se ajusten a partir de datos.

En este proyecto se busca explorar y comparar distintos modelos de aprendizaje supervisado de ML y DL, como también algoritmos de aprendizaje no supervisado como K-Means y DBScan aplicados a la predicción de la calidad del vino. Se pretende observar cómo se comportan ante diferentes condiciones, analizar su capacidad para generalizar, y evaluar su efectividad en un problema de clasificación con datos reales.

El propósito es analizar el comportamiento de los modelos, identificar sus fortalezas, reconocer sus límites, y entender en qué situaciones es más conveniente utilizar cada uno. De esta forma, se busca comprender no solo el funcionamiento de estas técnicas, sino también sus alcances prácticos en la resolución de problemas concretos.

## Objetivos

### General
Desarrollar varios modelos de IA, tanto supervisados como no supervisados que predigan la calidad del vino, utilizando técnicas de Machine Learning (ML) y Deep Learning (DL) y comparando su desempeño.

### Específicos
- Explorar y analizar el dataset para identificar patrones y relaciones entre las variables que más tengan impacto en la calidad del vino.

- Entrenar y evaluar diferentes modelos de Machine Learning, como Gaussian Naive Bayes, Random Forest y SVM, para predecir la calidad del vino. Comparar el rendimiento de los modelos utilizando métricas como la precisión, la matriz de confusión y el reporte de clasificación.

- Implementar y evaluar modelos de Deep Learning, como redes neuronales profundas, para la predicción de la calidad del vino. Ajustar la arquitectura del modelo, los hiperparámetros y las técnicas de regularización para optimizar el rendimiento.

- Utilizar los algoritmos de aprendizaje no supervisado de K-Means y DBScan para agrupar los distintos tipos de vino basandose en sus características fisicoquímicas y observar si estos clusteres corresponden a si efectivamente es un buen o mal vino.

