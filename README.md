# XGBoost

En el archivo 'XGBoost and gradient descent' se encuentra una pequeña demo con datos generados artificalmente en la que se intenta comparar la precision con la que ambos modelos predicen los parámetros para un modelo de regresión lienal simple, a la que se le añade un poco de ruido.


En el archivo XGBoost salarios encontramos un dataset de aproximadamente 32.000 individuos en la que se encuentra informacion sobre 14 variables, tanto categoricas como numéricas y una variable objetivo, si los individuos tienen un sueldo anual de +50K $ anuales. También se aáden algunas variables artificiales combinando o haciendo transformaciones de las variables originales para aumentar la cantidad de infromacion del modelo.
En este casso se utiliza un algoritmo de gradient boosting, y se utiliza un algortimo de validación cruzada que nos permite observar cuales son los parámetros mas óptimos para este set de datos.
Con el mejor estimador del modelo se obtiene una precisión del 87,5%

los datos han sido recopilados por la Universidad de california y s epueden encontrar en: https://archive.ics.uci.edu/ml/datasets/adult
