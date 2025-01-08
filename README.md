# PI1-Henry-Machine-Learning


Introducción:
El proyecto trata del análisis y recomendación para películas, diseñada para ayudar a los usuarios a explorar y descubrir películas basadas en sus preferencias personales. Utiliza técnicas avanzadas de análisis de datos para proporcionar recomendaciones precisas y personalizadas, basadas en el género, el director y otros criterios relevante.


CONJUNTO DE DATOS:
Para este pyoyecto Henry nos proporciono dos conjuntos de datos para poder realizar este proyecto.

movies_dataset.csv Este conjunto de datos contiene la información detallada de las peliculas, asi como otros datos como los votos hecha por el publico (usuarios), asi como proporciona el presupuesto para cada una de las peliculas

credits.csv En este conjunto de datos nos da la información de los actores y los directores que participaron en cada una de las peliculas, asi el rol que tienen cada uno de ellos.


Ingenieria de Datos(ETL):

En esta etapa inicial, se hizo un conjunto de cambios en los dos archivos originales, de los cuales se eliminaron datos duplicados, asi como eliminar columnas que ya inicialmente eran requisitos de eliminacion, asi como el ejecutar una función de desanidar las columnas que era una lista de diccionarios.

Creación de Funciones:
En esta etapa se utilizo FastApi para desarrollar una aplicación que contiene las funciones solicitadas por el cliente, de las cuales estas devuelven la información solicitada para cada instancia.

def cantidad_filmaciones_mes( Mes ): Se ingresa un mes en idioma Español. Debe devolver la cantidad de películas que fueron estrenadas en el mes consultado en la totalidad del dataset.

def cantidad_filmaciones_dia( Dia ): Se ingresa un día en idioma Español. Debe devolver la cantidad de películas que fueron estrenadas en día consultado en la totalidad del dataset.

def score_titulo( titulo_de_la_filmación ): Se ingresa el título de una filmación esperando como respuesta el título, el año de estreno y el score.

def votos_titulo( titulo_de_la_filmación ): Se ingresa el título de una filmación esperando como respuesta el título, la cantidad de votos y el valor promedio de las votaciones. La misma variable deberá de contar con al menos 2000 valoraciones, caso contrario, debemos contar con un mensaje avisando que no cumple esta condición y que por ende, no se devuelve ningun valor.

def get_actor( nombre_actor ): Se ingresa el nombre de un actor que se encuentre dentro de un dataset debiendo devolver el éxito del mismo medido a través del retorno. Además, la cantidad de películas que en las que ha participado y el promedio de retorno.

def get_director( nombre_director ): Se ingresa el nombre de un director que se encuentre dentro de un dataset debiendo devolver el éxito del mismo medido a través del retorno. Además, deberá devolver el nombre de cada película con la fecha de lanzamiento, retorno individual, costo y ganancia de la misma.

Analisis Exploratorio de Datos (EDA):
Se realizó un análisis comprensivo de los datos para entender la estructura y las características del conjunto con el que estamos trabajando. Esto implica examinar la distribución de variables, detectar valores atípicos y explorar las relaciones entre las variables, entre otros aspectos clave. Este análisis es fundamental para identificar patrones o tendencias en los datos, lo que permite formular hipótesis sólidas y diseñar modelos más precisos.
![image](https://github.com/user-attachments/assets/bdd8ec2a-d8d8-44f1-8ba0-7e3178fa8b1a)

![image](https://github.com/user-attachments/assets/7d9ce00e-10d3-4f7e-9286-82f0d2dfb230)

![image](https://github.com/user-attachments/assets/58824ba1-2905-4493-8dcc-460ffb4b9cbf)



Sistema de recomendación:
En el archivo "Sistema de recomendación" se encuentra la guía detallada de cómo se diseñó y desarrolló el modelo de recomendación. Este documento incluye una descripción de los pasos seguidos, desde la recopilación y preparación de datos hasta la implementación del algoritmo de recomendación. Además, se documentan los criterios y métricas utilizados para evaluar la efectividad del modelo, proporcionando una visión integral del proceso de creación del sistema de recomendación.
