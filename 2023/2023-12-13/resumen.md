# Título

Breve introducción a la asimilación de datos y su aplicación a modelos epidemiológicos

## Orador

Lic. Santiago Rosa, IFEG-CONICET, FaMAF-UNC

## Resumen 

La asimilación de datos es un conjunto de técnicas cuyo objetivo es combinar información de un modelo numérico con observaciones, con el objetivo de estimar mejor el estado de un sistema y/o obtener mejores condiciones iniciales para realizar pronósticos. Una técnica de asimilación de datos fácil de implementar y computacionalmente eficiente es el filtro de Kalman por ensambles. Dicha técnica es una aproximación de Monte Carlo del filtro de Kalman convencional, desarrollado para tratar con modelos grandes y gran cantidad de observaciones en el ámbito de la oceanografía y meteorología.
En este seminario realizaré una breve introducción al filtro de Kalman por Ensambles y cómo se puede aplicar a modelos epidemiológicos que simulan la evolución de COVID-19 en Argentina. Voy a mostrar que con sólo conocer casos y muertes divididas por rangos etarios es posible, bajo cierta parametrización, estimar la matriz de transmisión del virus entre grupos etarios. Esta estimación nos permite, usando un modelo tipo SEIR metapoblacional con matriz de transmisión, aumentar la precisión de pronósticos de nuevos casos comparado con un modelo donde toda la población está contenida en un solo grupo etario, y a estimaciones confiables del número de reproducción efectivo.
