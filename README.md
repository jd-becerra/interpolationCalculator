# Visit the website (only Spanish language supported)
# https://metodos-interpolacion.netlify.app/
![image](https://github.com/jd-becerra/interpolationCalculator/assets/112126654/3d882681-0ee4-4d51-a185-32274930d22e)

This project is an interactive tool to visualize and compare four linear interpolation methods, developed for a Discrete Mathematics course. It uses HTML, CSS, and JavaScript to compute and graph function approximations, showing the results and the error percentage.

## What is interpolation?

Interpolation is a mathematical technique that allows us to estimate the value of a function at a point located between other known data points. Imagine you have a series of measurements, but one value in the middle is missing; interpolation helps you predict that missing value based on the data you already have.

## Main Features

1. Explore and compare the results of the following interpolation methods:

   * **Linear**: Uses a straight line to connect two data points and estimate an intermediate value. It is the simplest method, but also the least accurate if the actual function is not linear.
   * **Quadratic**: Uses a parabola (second-degree function) that passes through three points to obtain a smoother and often more accurate approximation than linear interpolation.
   * **Lagrange first and second order**: These methods construct a polynomial that passes exactly through the data points. The first-order uses two points (like the linear method), while the second-order uses three points (like the quadratic), providing a more robust approximation.
2. Depending on the method used, two or three existing data points and a variable x for which the approximation of f(x) will be calculated are required.
3. Visualization with GeoGebra: Once the result is obtained, it will be graphed in a GeoGebra interface, showing the variable functions, the approximation of x, and its value.
4. Interpolation and extrapolation detection: The system labels in GeoGebra whether the approximation of x is an interpolation (within the data point range) or an extrapolation (outside the range).
5. Error analysis: Calculates and displays the relative error percentage between the approximate value of f(x) and a real value provided by the user, offering a metric of each method’s accuracy.

## Technologies Used

* HTML: For the structure of the web page.
* CSS: For the design and visual presentation.
* JavaScript: For the interpolation calculation logic and interaction with the GeoGebra API.
* GeoGebra API: For the graphical representation of functions and points on the Cartesian plane.

