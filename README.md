# COVID-19 Chile Coronavirus
(Todos los cálculos y gráficos fueron hechos con los datos oficiales del Ministerio de Salud de Chile).
## Este repositorio contiene:
* Database (CSV)
* Get data
* Map
* Notebook
* Screenshots (minsal)

### Database (CSV)
Database (CSV) contiene los archivos CSV con los datos oficiales de la pagina del [Ministerio de Salud de Chile](https://www.minsal.cl/nuevo-coronavirus-2019-ncov/casos-confirmados-en-chile-covid-19/) desde el 2020-03-09 hasta la fecha.
En Database encontraras 2 tipos de formato.
* Primer formato: En este se almacenan los datos de la primera tabla de la página del Ministerio de Salud (Región, Casos nuevos	, Casos totales, % Casos totales, Fallecidos).
* Segundo formato: En este se almacenan la suma de las columnas anteriores y los casos de recuperados (Casos recuperados a nivel nacional, Casos nuevos, Casos totales, Fallecidos, Fecha).

### Get data
Get data es un Jupyter Notebook en python que se encargar de obtener los datos de la página oficial del Ministerio de Salud, luego crea un archivo .csv con el primer formato (este documento se crea diariamente) y luego se encarga de actualizar diariamente el archivo "Resumen_COVID-19_Chile_.csv" con el segundo formato.

### Map
Map contiene un archivo .Geojson con el mapa de chile con sus 16 regiones, el cual utilizamos para mostrar los casos totales por región a la fecha, la prevalencia y la incidencia cada 100.000 habitantes a la fecha.

### Notebook
Notebook tiene un Jupyter Notebook en python en el cual hacemos un pequeño "análisis" (gráficos).

### Screenshots (minsal)
Screenshots (minsal) tiene screenshots o capturas de pantalla a los reportes dados por el Ministerio de Salud (las tablas que publican diariamente), he recopilado los reportes desde el 2020-03-09 hasta la fecha.

#### Nota: Este repositorio se actualizará todos los días entre las 12 y 14 del día, obviamente esto puede variar si el Ministerio de Salud se demora en entregar las cifras.