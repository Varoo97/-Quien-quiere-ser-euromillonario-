 ¿Quién quiere ser euromillonario?
![IMG_20221114_194239_604 (1)](https://user-images.githubusercontent.com/114336696/201741367-37996386-8b13-4036-8fc9-9390a7e4d6a0.jpg)

🎯 OBJETIVOS
- E -> Crear una base de datos mediante 2 metodos diferentes de extracción y 3 fuentes distintas
- T -> Transformar y limpiar los datos, de manera que sean significativos y útiles para nuestros objetivos
- L -> Cargar la base de datos 


🚶 PASOS QUE HEMOS SEGUIDO PARA ESTE PROYECTO

-El primer paso de nuestro proyecto es la carga de datos mediante la descarga de un archivo csv
![image](https://user-images.githubusercontent.com/114336696/201744583-87a81409-d034-4f1b-aa67-ffb7382a1ef8.png)

Limpiamos este DataFrame y exploramos un poco en él, para obtener datos como combinaciones repetidas o 5 números que más salen por posición

![image](https://user-images.githubusercontent.com/114336696/201748204-649ed867-da77-4d63-993f-c47b92fa2acc.png)
![image](https://user-images.githubusercontent.com/114336696/201748340-8f599c33-df79-4046-98d5-f042db473908.png)

Para la segunda fuente de información, hemos usado web scraping con Selenium, para la extracción de datos.
Una vez limpiamos los datos y nos quedamos con la información que nos interesa, nos da como resultado el siguiente DataFrame:

![image](https://user-images.githubusercontent.com/114336696/201749224-29cba36a-5039-436d-aee3-6c17fa1449cc.png)

Tras esto, concatenamos ambos DataFrames, y volvemos a limpiar los datos, dando como resultado:

![image](https://user-images.githubusercontent.com/114336696/201749913-193fee0b-c10b-40bd-a2e5-9b8b8ecfe633.png)

Finalmente extraemos los datos de la tercera fuente, mediante el mismo método de la primera (archivo.csv) y repetimos proceso de limpieza y extracción de datos significativos.

El DataFrame definitivo quedaría así:

![image](https://user-images.githubusercontent.com/114336696/201750886-5e310208-cf9e-4d05-b88f-fe5a2c8d425c.png)
![image](https://user-images.githubusercontent.com/114336696/201751091-0fb0fcea-f194-444b-b3e4-75c622ab13a9.png)

Para finalizar subimos la base de datos MySQL Workbench
![image](https://user-images.githubusercontent.com/114336696/201751698-685e9a38-54ed-44ae-bb2a-a8b2f87bff2d.png)

