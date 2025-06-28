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
* Se minimiza una función de coste (también conocida como función de error) $j \left( \theta \right)$ para obtener los parámetros $\theta_0$ y $\theta_1$ óptimos


La función de error calcula la diferencia entre el valor observado y la predicción estimada por la función de hipótesis.

**Función de coste**

En RL la función de coste más comun que se suele utilizar es **Mean Square Error** (MSE).
La función de error se determina de la siguiente forma:

<p align="center"> $j \left( \theta \right) = \frac{1}{2m} \sum_{i=1}^{m} \left(h\theta \left(x^{(i)} \right) - y^{(i)} \right)^{2} $ </p>

Se pueden aplicar distintas funciones de coste a un mismo algotimo de ML 
