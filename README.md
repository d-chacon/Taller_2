# Taller 2: Regresión Lineal

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/d-chacon/Taller_2)


## **5. Generación de Resultados**

En cuanto a los coeficientes, se observa que la cobertura de población con acceso a internet tiene más fuerza con relación al PIB. Es interesante recalcar la relación de los casos de cancer de mama con el aumento del PIB, ya que tiene más fuerza que la variable de población que vive en zonas urbanas.

Otro insight interesante es la relación negativa entre la expectativa de vida y l PIB, intuitivamente se creería que una expectativa de vida mayor contribuiría a un mayor PIB; pero de acuerdo a la regresión es al contrario.

Como es común, los valores de test son más altos que los valores de train. Se considera que presenta un valor alto de error (underfitting) ya que existen paises cuyo pib ronda los cientos de dólares, por lo que un error de 5000 dólares no sería aceptable. Se recomienda agregar más variables de entrada al modelo, o integrar más datos correspondientes a otros años.

Un aspecto positivo es el R<sup>2</sup>, ya que captura el 80% de la varianza de los datos; sin embargo se cuentan con muy pocos registros para dar con una predicción acertada.

Se proponen dos políticas públicas para mejorar los aspectos de cobertura a población con acceso a internet y cobertura de la población en zonas urbanas:
* Inversión en infraestructura: El gobierno puede promover la inversión en infraestructura de telecomunicaciones, como la expansión de redes de fibra óptica y la construcción de torres de telefonía móvil en áreas rurales y remotas donde la cobertura es deficiente.
* Programas de capacitación y educación: Ofrecer programas de capacitación y educación que preparen a la población rural para trabajos urbanos y ayuden a mejorar sus perspectivas laborales en las ciudades.
