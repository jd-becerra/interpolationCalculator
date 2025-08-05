# Visita la página: 
# https://metodos-interpolacion.netlify.app/
![image](https://github.com/jd-becerra/interpolationCalculator/assets/112126654/3d882681-0ee4-4d51-a185-32274930d22e)

Este proyecto es una herramienta interactiva para visualizar y comparar cuatro métodos de interpolación lineal, desarrollada para la clase de Matemáticas Discretas. Utiliza HTML, CSS y JavaScript para calcular y graficar aproximaciones de funciones, mostrando los resultados y el porcentaje de error.

## ¿Qué es la interpolación?

La interpolación es una técnica matemática que nos permite estimar el valor de una función en un punto que se encuentra entre otros puntos de datos conocidos. Imagina que tienes una serie de mediciones, pero te falta un dato intermedio; la interpolación te ayuda a predecir ese valor faltante basándote en los datos que ya tienes.

## Características Principales

1. Explora y compara los resultados de los siguientes métodos de interpolación:
    - **Lineal**: Utiliza una línea recta para conectar dos puntos de datos y estimar un valor intermedio. Es el método más simple, pero también el menos preciso si la función real no es lineal.
    - **Cuadrático**: Utiliza una parábola (función de segundo grado) que pasa por tres puntos para obtener una aproximación más suave y, a menudo, más precisa que la interpolación lineal.
    - **Lagrange de primer y segundo orden**: Estos métodos construyen un polinomio que pasa exactamente por los puntos de datos. El de primer orden usa dos puntos (como el lineal), mientras que el de segundo orden usa tres puntos (como el cuadrático), proporcionando una aproximación más robusta.
2. Según el método utilizado,  se requerirán dos o tres puntos de datos existentes y una variable x para la cual se calculará la aproximación de f(x).
3. Visualización con GeoGebra: Unas vez obtenido el resultado, se graficará en una interfaz de GeoGebra, mostrando las funciones de las variables, la aproximación de x y su valor.
4. Detección de interpolación y extrapolación: El sistema etiqueta en Geogebra si la aproximación de x es una interpolación (dentro del rango de los puntos de datos) o una extrapolación (fuera del rango).
5. Análisis de error: Calcula y muestra el porcentaje de error relativo entre el valor aproximado de f(x) y un valor real proporcionado por el usuario, ofreciendo una métrica de la precisión de cada método.

## Tecnologías Utilizadas
- HTML: Para la estructura de la página web.
- CSS: Para el diseño y la presentación visual.
- JavaScript: Para la lógica de cálculo de las interpolaciones y la interacción con la API de GeoGebra.
- GeoGebra API: Para la representación gráfica de las funciones y los puntos en el plano cartesiano.
