<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100" align="center"/>

<img src="img/banner.jpg">


# Project: Visualizing Real World Data


Mar Lizana Atienza

*Data Part Time Barcelona Dic 2019*


## Content

**Índice**   
1. [Project Description](#id1)
2. [Dataset](#id2)
3. [Workflow](#id3)
3. [Results](#id4)



<a name="project"></a>

## Project Description<a name="id1"></a>

En este projecto nos centraremos en la visualización de un dataset. Para ello usaremos las herramientas vistas en clase, entre las que incluiremos elementos interactivos y gráficos de correlación entre otros.
El código está comentado para cualquier otra duda.


<a name="dataset"></a>

## Dataset<a name="id2"></a>

Hemos seleccionado un dataset de la plataforma Kaggle sobre <a href="https://www.kaggle.com/dannielr/marvel-superheroes/">superhéroes de Marvel</a>. Este conjunto de datos está organizado en diferentes .csv:

* <b>characters.csv</b>. 2 columnas: <CODE>characterID</CODE> y <CODE>name</CODE>.
* <b>charactersToComics.csv</b>. 2 columnas: <CODE>comicID</CODE> y <CODE>characterID</CODE>.
* <b>charcters_stats.csv</b>.  9 columnas: <CODE>Name</CODE>, <CODE>Alignment</CODE>,<CODE>Intelligence</CODE>, <CODE>Strength</CODE>,<CODE>Speed</CODE>, <CODE>Durability</CODE>,<CODE>Power</CODE>, <CODE>Combat</CODE> y <CODE>Total</CODE>.
* <b>comics.csv</b>. 4 columnas: <CODE>comicID</CODE>, <CODE>title</CODE>,<CODE>issueNumber</CODE> y <CODE>description</CODE>.
* <b>marvel_characters_info.csv</b>. 11 columnas: <CODE>ID</CODE>, <CODE>Name</CODE>,<CODE>Alignment</CODE>,<CODE>Gender</CODE>, <CODE>EyeColor</CODE>,<CODE>Race</CODE>,<CODE>HairColor</CODE>, <CODE>Publisher</CODE>,<CODE>SkinColor</CODE>,<CODE>Height</CODE> y <CODE>Weight</CODE>.


 --> Selección de columnas entre los diferentes csv

<a name="workflow"></a>

## Workflow<a name="id3"></a>

El recorrido del proyecto es el siguiente:

1. Introducción
2. Preparar los datasets, examinar y analizar
3. Análisis estadístico y visualización
4. Grafo

<a name="results"></a>

## Results<a name="id4"></a>

- Gráficos interactivos para correlaciones, spiderplots según personaje, diagramas de cajas y bigotes por característica según sexo y alineación y, finalmente dos grafos, un egograph de cada personaje y uno general con las relaciones entre personajes.




