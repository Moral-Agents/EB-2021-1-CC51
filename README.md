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
### 1.- ¿Es factible predecir el número de “Vistas”, “Me gusta” o “No me gusta”?
Sí es factible predecir las 3 variables. Con los coeficientes obtenidos se puede concluir estas predicciones:
#### Predicción de views:
Manteniendo todas las demás características fijas, un aumento de 1 unidad en likes está asociado con un incremento de 11 views.
Manteniendo todas las demás características fijas, un aumento de 1 unidad en dislikes está asociado con un incremento de 705 views.
#### Predicción de likes:
Manteniendo todas las demás características fijas, un aumento de 1 unidad en views está asociado con un incremento de 0.002 likes.
Manteniendo todas las demás características fijas, un aumento de 1 unidad en dislikes está asociado con un incremento de 5 likes.
#### Predicción de dislikes:
Manteniendo todas las demás características fijas, un aumento de 1 unidad en dislikes está asociado con un incremento de 11 views.
Manteniendo todas las demás características fijas, un aumento de 1 unidad en dislikes está asociado con un incremento de 705 views.


# Licencia
Este repositorio usará la licencia https://opensource.org/licenses/MIT.

