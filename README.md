ooooo

# REGRESIÓN LINEAL.

**Características**

* Es un algorítmo de prendizaje supervisado
* Es un algoritmo de aprendizaje basado en modelos.
* Se corresponde con un modelo lineal.
* Realiza predicciones computando una suma ponderada de las características de entrada y sumandole una constante conocida como *bias*
* Intenta predecir **valores continuos**

**Conjunto de datos de entrenamiento**

- *x* Variable de entrada (feature)
- *y* Variable de salida (target value)
- (*x*,*y*) conjunto de datos (dataset)

**Funcion Hipótesis**
Un modelo no es más que la función de hipotesis, despues de haberse ajustado al dataset.
La función de hipótesis de una regresión lineal se expresa de la siguiente forma:

<p align="center"> $h_\theta \left( x \right) = \theta_0 + \theta_1 x$ </p>

En otras palabras, es la **ecuación de la recta**.

Como se observa el término constante es $\theta_0$ , tambien conocido como **término baias**

**Construcción del modelo**

* Buscar los parámetros $\theta_0$ y $\theta_1$ que generen la función de hipótesis $h_\theta \left( x \right)$ que mejor se adapte al conjunto de datos de entrenamiento (*x*,*y*).
* Se minimiza una función de coste $j \left( \theta \right)$ para obtener los parámetros $\theta_0$ y $\theta_1$ óptimos
