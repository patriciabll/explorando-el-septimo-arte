## Proyecto CinemExtract: Explorando el Séptimo Arte a través de Datos y Tecnología
Este repositorio contiene el código y la documentación para un proyecto basado en el análisis de datos utilizando Python, Selenium, Beautiful Soup y SQL
Analizamos las películas y cortometrajes desde 1990 hasta diciembre de 2023 de una plataforma de streaming, ayudandoles así a tomar decisiones sobre qué contenido promocionar y destacar, y dando ideas para futuros pasos basado en el análisis de datos


## Estructura del repositorio:
FASE I: 
Extraemos los datos de las películas de la API MoviesDataset organizadas por género
Datos a extraer:
    - Tipo (si es corto o película)
    - Nombre de la película o el corto
    - Año de estreno de la película o corto
    - Mes de estreno de la película o corto
    - Id de la película

Dcumentos: proyecto2_chicas10_fase_1.ipynb ==> peliculas.csv 


FASE II: 
Extraemos los detalles de películas con Selenium de las páginas web IMBD y Rotten Tomatoes
Datos a extraer:
    - Puntuacion de IMDB (en caso de que la tenga)
    - Puntuación de Rotten Tomatoes (Tomatometer)
    - Dirección (director/a o directore/as de cada película)
    - Guionistas (de cada película)
    - Argumento.
    - Duración (en minutos)
    - Nombre de la película

 Documentos: proyecto2_chicas10_fase_2.ipynb ==> detalle_peliculas.csv y tomatometro.csv


FASE III: 
Extraemos los detalles de actores/actrices con Selenium
Datos a extraer:
    - Nombre
    - Año nacimiento
    - ¿Por qué es conocido?
    - ¿Qué hace?
    - Premios                                        

Documentos: proyecto2_chicas10_fase_3.ipynb ==> peliculas_artista.csv y detalles_artista.csv


FASE IV: 
Extraemos la tabla de los premios Oscar con Beautiful Soup
Datos a extraer:
    - Fecha de la ceremonia
    - Mejor película
    - Mejor director
    - Mejor actor
    - Mejor actriz

Documentos: proyecto2_chicas10_fase_4_oscars_bsoup.ipynb ==> oscars.csv
    

FASE V: 
Diseño de la BBDD con SQL

Documento: encabezados_y_calendario.xlsx


FASE VI: Inserción de datos en la BBDD

    creacion_tablas.sql para el diseño de la bbdd
    bbdd_whatflix.sql - la bbdd de trabajo y análisis

FASE VII: 
Realizamos consultas a la BBDD para sacar conclusiones

Documento: CONSULTAS.sql


WHATFLIX_demo.pptm:
Presentación para el cliente ficticio que nos ha solicitado el servicio


## Equipo:
- Ana González - @AnaGonzalez10
- Patricia Blanco - @patriciabll
- Rocío Gorgojo - @MRocioG
- Clara Avecilla - @clarasdata