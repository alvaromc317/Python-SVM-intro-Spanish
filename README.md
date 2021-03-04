# Introducción a las SVM en Python

¡Bienvenidos a este curso de introducción a las SVM en español! La estructura y códigos de de este curso está basada en parte en el libro 
* [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)

Este curso se divide en cuatro sesiones a lo largo de las cuales veremos qué son las SVM, cómo utilizarlas en Python y qué es el conocido como _kernel trick_. También trabajaremos analizando dos conjuntos de datos reales, uno de un problema de clasificación y otro de regresión, para lo cual repasaremos conceptos habituales del campo del machine learning (división train / test, validación cruzada, métricas que podemos utilizar...) A lo largo del curso tendréis varios ejercicios breves para ir resolviendo que afianzarán los conceptos vistos hasta ese momento. Las respuestas de los ejercicios están en la carpeta _svm_soluciones_.

Veamos la estructura general del curso:

1. __svm_intro__: En esta libreta planteamos los conceptos básicos de las SVM: qué son, en qué problemas se pueden utilizar, cómo podemos usar las SVM en Python, qué es el kernel trick, y cómo usar los principales kernels (polinómico y rbf)
2. __svm_mnist__: En esta libreta nos centramos en analizar un conjunto de datos real, llamado MNIST, que define un problema de clasificación de imágenes de dígitos escritos a mano. ¿podremos construir una SVM que haga una buena clasificación de estos dígitos? Este problema nos permitirá introducir conceptos como la necesidad de dividir los datos en train / test y de usar validación cruzada (y cómo podemos hacer esto facilmente en Python). También veremos distintas métricas que pueden ser importantes en problemas de clasificación (precision, recall, curva roc) y que debemos tener presente además de la tasa de aciertos. Por último veremos cómo podemos buscar los valores óptimos de una SVM utilizando las técnicas de grid search y random search.
3. __svm_regresion_and_outliers__: En esta libreta introducimos brevemente dos problemas en los que las SVM también pueden ser utilizadas además de en clasificación: problemas de regresión, donde la variable respuesta es numérica, y problemas de detección de outliers, en los que no hay una variable respuesta y el objetivo es buscar observaciones con un comportamiento anómalo.
4. __svm_california_housing__: En esta libreta trabajaremos con un conjunto de datos con información sobre el precio de las casas en el estado de California. El objetivo será construir una SVM de regresión que nos permita predecir el precio de estas casas. Aquí introduciremos el uso de pipelines en el preprocesado de los datos, el tratamiento de las variables categóricas para incluirlas en nuestros modelos (para lo que usaremos el llamado one-hot encoding) y el uso de métricas como el error cuadrático medio.

Así que... ¡Empecemos!
