# Práctica final del módulo de Deep Learning
## Objetivo
El objetivo de la práctica final del módulo de Deep Learning consiste en resolver un problema
del mundo real empleando para ello técnicas vistas durante las sesiones de dicho módulo.
En concreto, se trabajará en predecir el precio de habitaciones de AirBnB utilizando para ello
todas las características disponibles en el dataset.
El propósito no es obtener un sistema predictor con una precisión o una tasa de acierto lo
más alta posible, sino el diseño, implementación y la evaluación de modelos de redes
neuronales profundas que usen diferentes fuentes de datos (modalidades): numéricas e
imágenes.
## Dataset
Por continuidad con módulos anteriores se prefiere proseguir con un conjunto de datos de
AirBnB, que será proporcionado por el profesor en su formato tabular.
Por cuestiones de homogeneidad, se tomará el mayor número posible de muestras (por
tanto, el mismo número de imágenes) para la realización de esta práctica. Junto con este
enunciado se proporciona una herramienta que ayudará al alumno a obtener el conjunto de
datos completo que usar con la práctica.
Cabe la posibilidad de que en el momento de realizar la práctica, alguna de estas imágenes
no esté disponible. En ese caso, se procurará contar con tantas imágenes como sea posible.
## Tarea
Diseñar, implementar y evaluar una serie de algoritmos predictivos basados en redes
neuronales profundas, así como en una combinación de los mismos, para la tarea de
predicción del precio de habitaciones en AirBnb.
Dicha tarea puede ser abordada de manera indistinta como una clasificación de rangos de
precios (clasificación) o una predicción directa del valor del precio (regresión).
A su vez, la tarea se compone de 4 secciones, cuya finalización completa se exige para
superar con éxito el módulo:
1. Modelo 1D/tabular: Emplear al menos 1 red neuronal profunda basada en capas
Dense para realizar la predicción a partir de datos tabulares.
2. Modelo 2D/imágenes: Emplear al menos 1 red neuronal profunda basada en capas
convolucionales o capas de atención (Transformers) para realizar la predicción a
partir de imágenes.
a. Es importante destacar que el alumno debe priorizar el empleo de
arquitecturas pre-entrenadas, congelando la parte ya entrenada del modelo y
obteniendo embeddings que le permitan afrontar el problema de manera ágil
empleando luego un clasificador basado en capas Dense de su elección.
b. Tan sólo en el caso de que el alumno disponga de tiempo, se le anima a que
de manera opcional entrene por completo un modelo 2D. Sin embargo, se
recomienda completar primero toda la práctica antes de abordar este punto.
3. Estrategia late-fusion: Empleo de 1 modelo DL/ML que sea capaz de combinar las
predicciones realizadas por un modelo 1D y por un modelo 2D para realizar a su vez
la predicción.
4. Estrategia early-fusion: Empleo de 1 modelo DL/ML que sea capaz de combinar los
embeddings obtenidos por un modelo 1D y por un modelo 2D para realizar a su vez la
predicción.
