Jupyter Notebook para acceder a la API de Marvel, que ofrece algunos datos sobre cómics, series o creadores.

Es necesario el registro previamente en https://developer.marvel.com, donde se facilitará 2 claves (pública y privada) que deberán introducirse en el código. 

En mi caso he optado por exportar esta información de cómics: título, descripción, UPC, URL, creadores y precio. La elección ha sido bastante al azar, pues lo que me interesaba realmente era poder acceder.

El resultado es un dataframe con las variables mencionadas.

Ejercicio realizado meramente como aproximación a las APIs.

Ejemplos de endpoints que puedes consultar para obtener diferentes tipos de datos:

Comics: https://gateway.marvel.com/v1/public/comics
Characters: https://gateway.marvel.com/v1/public/characters
Creators: https://gateway.marvel.com/v1/public/creators
Events: https://gateway.marvel.com/v1/public/events
Series: https://gateway.marvel.com/v1/public/series
Stories: https://gateway.marvel.com/v1/public/stories


Documentación de la API: 
https://developer.marvel.com/documentation/getting_started
https://developer.marvel.com/documentation/generalinfo
https://developer.marvel.com/documentation/entity_types
