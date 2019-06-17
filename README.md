# Trabajo Final
Objetivo: Evaluar la habilidad de los estudiantes para comunicar ideas utilizando tecnologías para la web

# Publicación de cartografía vía web
Comunicar una historia de través de tecnologìas para la publicación web utilizando mapas interactivos y elementos multimedia.
## Investigadores:
#### Lorena Rayo Rocha `3101451`
#### Fernando Alcarcel Gutierrez `3101441`
#### Albeiro López Pulido `3101446`
---
Histórico de sismos y su relación con la geología.

## 1. Cuál es el problema a tratar?

Se busca documentar a toda clase de lector sin conocimientos previos de geología acerca de la relación de las placas tectónicas con los movimientos sismicos, haciendo un repaso histórico por los registros más antiguos registrados en Colombia


## 2. Por qué una experiencia interactiva ayuda a resolverlo?

La interactividad de los mapas presentados ayudan al lector a hacer sus propias conclusiones, modificando los datos mostrados segun lo considere, y no es necesario conformarse con la informacion presentada en primera instancia por quien ofrece la información, ésto se logra a partir de filtros que se pueden aplicar, acercamientos a zonas de interes sobre los mapas interactivos, u observar los datos de las graficas interactivas correspondientes. 

## 3. Descripción de los datos (tipos de geometrías, atributos, sistemas de referencia, urls para descarga de la información, etc)

Para la realización de este trabajo Obtuvieron diferentes clases de datos, los cuales fueron desde tabla de datos hasta poligonos de las placas tectónicas de la tierra, dicha información geogáfica fue complementada con registros históricos de periodicos que por su descripción permiten su localización espacial y temporal. Las fuentes de información fueron: 

https://www.datos.gov.co/Ambiente-y-Desarrollo-Sostenible/Precipitaci-n-Media-Total-Anual-Promedio-Multianua/2bm3-399z 

Catalogo nacional de estaciones metereológicas: https://www.datos.gov.co/Ambiente-y-Desarrollo-Sostenible/Cat-logo-Nacional-de-Estaciones-del-IDEAM/hp9r-jxuu/data


## 4. Descripción del procesamiento realizado a los datos (ejm: transformaciones, filtros, geoprocesamiento, etc)

Para el desarrollo de este estudio se hicieron los siguiente procesos:

**Creación de archivo .shp:** Para el archivo de puntos correspondiente a los eventos sismicos del país, se tomaron los datos crudos en tabla de excel y con la ayuda del software ArcMap se convirtieron a formato .shp de tipología de punto con todos sus atributos. 

**Descarga del archivo .shp:** Los poligonos utilizados en el estudio se descargaron directamente en formato .shp y se cargaron de forma fácil en la herramienta Carto. 

## 5. Descripción de las diferentes técnicas y métodos utilizados para la visualización de datos.

La visualización de datos se realizo de forma grafica de diferentes formas: en forma de mapa para los datos georeferenciados que hacen referencia a los eventos sismicos en Colombia y en el Mundo, por otra parte los datos fueron tratados estadisticamente y se presentan en graficas para dimensionar los resultados. Los datos temporales fueron localizados de forma ordenada en el mapa de Colombia para ambientar su localizacion y temporalidad. 

## 6. Descripción breve de las diferentes herramientas y procedimientos utilizadas para publicar el contenido en la web.

Para la visualización, analisis de datos y compartir los resultados de manera ágil, se seleccionaron dos herramientas: 

**Mapbox:** [Carto](https://Mapbox.com/) 

Inicialmente se utilizó la herramienta [Mapbox](https://Mapbox.com/) para elaborar un estilo que facilitara localizar cada evento sismico de manera clara, reduciendo los contrastes entre los objetos del mapa base, para resaltar los eventos sismicos.  

**Carto:** [Carto](https://carto.com/) 

Inicialmente se utilizó la herramienta [Carto](https://carto.com/) con la cual es posible no solo cargar los datos adquiridos, sino analizarlos de diferente forma con diferentes herramientas para obtener más información de la que por si tienen en sus atributos. Inicialmente se realizo un cambio de estilo al mapa cargando el estilo elaborado en la herramienta Mapbox, posteriormente se cargaron los datos en formato SHP correspondientes a sismos en el mundo, los sismos en Colombia, y los polígonos de las placas tectónicas de la tierra. 

**Storymap** [Storymap](https://storymap.knightlab.com/)

La herramienta "Storymap" permite de forma clara organizar eventos espacial y temporalmente, lo cual es ideal para ilustrar la disposición en el planeta de los diferentes eventos que generan los movimientos sismicos. 

**Visme** [Visme](https://my.visme.co/)

Herramienta especializada en la visualización de datos estadisticos de forma clara y dináica para que el lector pueda conocer todos los datos graficados y consultarlos en el orden que desee, adicional a ello con sus movimientos le da una dinámica a las graficas interesantes. 

**Slides** [Slides.com](https://www.slides.com/)

Ésta herramienta especializada en la presentación de datos de forma clara, nos permitió reunir toda la información elaborada en diferentes herramientas y mostrarla de forma ordenada para que observador entienda en forma de flujo el análisis de los sismos a travéz de la historía. 


## 7. Ventajas / desventajas / dificultades de la publicación de mapas utilizando herramientas en la nube respecto al software desktop.

ventajas:

1. Los mapas se encuentran disponibles las 24 horas del día, los 7 días de la semana.
2. No se necesita software especializado.
3. Los mapas en la web son fáciles de consumir.
4. Se obtienen mapas amigables en entornos agradables y sofisticados muy sencillos de usar.
5. No hace falta ser experto en programación y desarrollo web para publicar mapas.
6. No hace falta almacenar la información en un repositorio local, todo queda en la nube.
7. Es colaborativa y facilita el intercambio de información geoespacial.

desventajas:

1. El costo en los servicios de paga, ya que un servicio gratuito es limitado en funcionalidad y capacidad de almacenamiento.
2. El acceso a la información está supeditado a los servicios de internet, es decir que siempre es necesario contar con este servicio para consumir mapas web.
3. Las herramientas de los servicios web de mapas son limitadas y reducidas.

dificultades:

1. Simplificar la información geoespacial para llegar a un mayor numero de usuarios.
2. Cambiar el lenguaje especializado para que pueda ser comprendido por un publico más amplio. 

Url público de la experiencia interactiva

`Url público de la experiencia interactiva`

https://slides.com/geomaticos/deck-1


