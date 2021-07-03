# EB-2021-1-CC51
# Objetivo
Este proyecto tiene como objetivo general la creación de conocimiento, específicamente queremos conocer las características de las tendencias  de los videos de Youtube en India. Esta información que se quiere conocer es la responde a las siguientes preguntas:

#### Por Categoría de Videos
1. ¿Qué categorías de videos son las de mayor tendencia?
2. ¿Qué categorías de videos son los que más gustan? ¿Y las que menos gustan?
3. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”?
4. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” / “Comentarios”?

#### Por el tiempo transcurrido
5. ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?

#### Por Canales de YouTube
6. ¿Qué canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?

#### Por la geografía del país
7. ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?

Además, se busca estimar qué relación hay entre los views y  los likes & dislikes.

# Integrantes
* Altamirano Higa, Marco - u201919054
* Moreno Vidal, Gabriel - u201913263
* Morales Linares, Stephano Heli - u201912659

# Breve Descripción del Dataset
Para lograr los objetivos planteados realizaremos un análisis exploratorio del dataset “Trending YouTube Video Statistics India” (INvideos_cc50_202101)  obtenido de:
https://drive.google.com/file/d/1tM5qFHIW-8fsodvVUi2Tpz20LNL4Yo86/view. Este conjunto de datos contiene el registro diario de los videos de YouTube de mayor tendencia en India, entre los meses de noviembre de 2017 a junio de 2018. Consiste en 31737 observaciones que representan videos y su fecha en la que estuvieron en tendencia, con 20 variables que las describen.

# Conclusiones
# A
### 1.- ¿Qué categorías de videos son las de mayor tendencia?
De un total de 36834 videos en tendencia, la categoría entretenimiento es la de mayor tendencia con 16457 videos, al cual le sigue la categoría política & noticias con 5155 videos, el tercer lugar lo ocupa la categoría música con 3792 videos. Los últimos lugares están ocupados por las categorías películas, viajes y animales con 16,8,2 videos respectivamente.

### 2.- ¿Qué categorías de videos son los que más gustan? ¿Y las que menos gustan?
Las categorías que más gustan son entretenimiento, música y comedia con 390775502, 245529963, 172728073 likes respectivamente y las categorías que menos gustan son animales,activismo y viajes con 361228, 218112 y 16939 likes respectivamente.

### 3.- ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”?
Las 3 categorías de videos con mayor proporción de “Me gusta”/”No me gusta” son Animales, Educación y Viajes con 56.82,30.26 y 27.50 de ratio respectivamente.

### 4.- ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” / “Comentarios”?
Las 3 categorías de videos con mayor proporción de “Vistas”/”Comentarios” son Shows, Películas y HowTo con 1331.16,1327.52 y 988.46 de ratio respectivamente.

### 5.- ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?
En noviembre del 2017 habían 3208 videos en tendencia, en los siguientes 6 meses hubo un aumento de este volumen con 5744, 5301, 4754, 5275, 4401, 5582 respectivamente. Finalmente, el volumen de videos decayó en junio del 2018 con 2479 videos.

### 6.- ¿Qué canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?
Los canales de Youtube que son tendencia más frecuentemente son VikatanTv, etvteluguindia y Flowers Comedy con 280, 280 y 270 veces en tendencia respectivamente. En cambio, “Indian World”, “REPUBLIC NEWS KANNADA” y “Challenge Mantra” aparecieron solo una vez en tendencia.

### 7.- ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?
El Estado con el mayor número de Vistas es Nagaland con un total de 1428962190.
El Estado con el mayor número de Me gusta es Nagaland con un total de 39561372.
El Estado con el mayor número de No me gusta es Nagaland con un total de 3270171.


# B
### 1.- ¿Es factible predecir el número de “Vistas”, “Me gusta” o “No me gusta”?
Sí es factible predecir las 3 variables. Con los coeficientes obtenidos se puede concluir estas predicciones:
#### Predicción de views:
Manteniendo todas las demás características fijas, un aumento de 1 unidad en likes está asociado con un incremento de 25.08 views.
Manteniendo todas las demás características fijas, un aumento de 1 unidad en dislikes está asociado con un incremento de 37.50 views.
Con las métricas halladas se concluyó que:
- La media del valor absoluto de lo errores es 625193.54
- La media de los errores al cuadrado es 2507126571080.55
- La raíz cuadrada de la media de los errores al cuadrado es 1583390.85
#### Predicción de likes:
Manteniendo todas las demás características fijas, un aumento de 1 unidad en views está asociado con un incremento de 0.025 likes.
Manteniendo todas las demás características fijas, un aumento de 1 unidad en dislikes está asociado con un incremento de 0.176 likes.
Con las métricas halladas se concluyó que:
- La media del valor absoluto de lo errores es 17984.26
- La media de los errores al cuadrado es 2524430791.23
- La raíz cuadrada de la media de los errores al cuadrado es 50243.71
#### Predicción de dislikes:
Manteniendo todas las demás características fijas, un aumento de 1 unidad en likes está asociado con un incremento de 0.011 dislikes.
Manteniendo todas las demás características fijas, un aumento de 1 unidad en views está asociado con un incremento de 0.002 dislikes.
Con las métricas halladas se concluyó que:
- La media del valor absoluto de lo errores es 2014.56
- La media de los errores al cuadrado es 207924890.09
- La raíz cuadrada de la media de los errores al cuadrado es 14419.60

### 2.- ¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?
En conclusión, los videos en tendencia sí tienen más comentarios positivos que negativos, ya que se puede ver que del total hay 35428 con más comentarios positivos, a diferencia de los negativos que solo hay 475.
Asimismo, los videos con mayor tendencia tienen más que los que están menos tendencia. Esto se sacó de una muestra de los 100 primeros y los 100 últimos. En los 100 primeros,
todos tenían más comentarios positivos, dejando en 0 los negativos. En cambio, los 100 últimos sólo tenían 94 videos con más comentarios positivos.



# Licencia
Este repositorio usará la licencia https://opensource.org/licenses/MIT.

