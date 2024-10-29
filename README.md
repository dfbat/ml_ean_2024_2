# Proyecto 2 en CD

***Diego Benavides***


Este trabajo analiza dos conjuntos de datos, por un lado se abarca el modelo de los vinos rojos y por el otro de los vinos blancos, s eprocede a realizar una breve conclusión de los dos casos:

***Vinos Blancos***
El modelo tiende a clasificar mejor los vinos de alta calidad, auque cuenta con una cantidad considerable de de falsos negativos que indican que algunos vinos de buena calidad se clasificaron incorrectamente.

716 vinos de buena calidad fueron clasificados correctamente y 112 no.


Para los vinos blancos de baja calidad, el modelo obtuvo más errores clasificando solo 197 de forma correcta y 200 incorrectamente.

En total los estadisticos de validación arrojaron los siguientes datos:
- Exactitud: 74%
- Precisión: 78%
- Sensibilidad: 86%
- Valor F1: 82%

conclusión: pese a tener estos valores en los estadisticos, se evidencia que el modelo clasifica mejor los vinos de buena calidadd (1) a la luz del resultado de su sensibilidad y F1.

--------------------------------------------------------------------------------

***Vinos Rojos***

El modelo clasifica correctamente el 75% de los vinos rojos, su precisión varía de acuerdo a la clase, ya que para los vinos de buena calidad, el modelo acierta en un 77% y para los de baja calidad un 68%.

Su capacidad de identificar los positivos reales es de 73%

El valor de la media armónica es relativamente alto, mostrando que la media entre la precisión y sensibilidad es del 75%.



