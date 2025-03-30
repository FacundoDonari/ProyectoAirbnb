
Análisis de Alquileres Temporales en Airbnb - Ciudad Autónoma de Buenos Aires (2025)

📊 Objetivo del Proyecto📊
Este proyecto de análisis de datos tuvo como objetivo principal investigar el comportamiento del mercado de alquileres temporales en Airbnb dentro de la Ciudad Autónoma de Buenos Aires durante el año 2025. A través de este análisis, buscamos responder preguntas clave como:

¿Cuáles son los tipos de alojamiento más ofertados y sus precios promedio?

¿Cómo varían los precios según la temporada y la cantidad de noches mínimas?

¿Qué barrios presentan mayor oferta y cuáles tienen los precios más elevados?

¿Existen patrones estacionales en la disponibilidad y precios?

🔎 Metodología

1. Extracción y Limpieza de Datos

Trabajé con dos archivos CSV principales: listings y calendar, los cuales compartían una columna de ID para su posterior unión.
Fuente: https://insideairbnb.com/get-the-data/

Realicé un proceso exhaustivo de limpieza en Python que incluyó:

✅ Eliminación de valores nulos

✅ Eliminación de columnas irrelevantes para el análisis

✅ Conversión de tipos de datos para optimizar el procesamiento

✅ Normalización de formatos y categorías

2. Procesamiento y Exportación
Los datasets limpios fueron exportados a nuevos archivos CSV optimizados para su análisis en Tableau.

3. Visualización y Análisis
Utilicé Tableau para crear dashboards interactivos que permitieran explorar las distintas métricas identificadas.

Desarrollé visualizaciones que muestran:

✅ Variaciones de precios por tipo de oferta y temporada

✅ Distribución geográfica de la oferta por barrios

✅ Relación entre precios y noches mínimas requeridas



 ⬛ Hallazgos Principales ⬛

Oferta y Precios por Tipo de Alojamiento:

▪ Los Departamentos o Casas Enteras son el tipo de alojamiento más ofertado (+3800), con un precio promedio destacado de $84.000.

▪ Se observa una clara diferencia de precios entre los distintos tipos de propiedad. (Habitacion privada y Casa/Depot)

Distribución Geográfica:

▪ Palermo, Recoleta y San Nicolás son los barrios con mayor oferta de alquileres temporales.

▪ Barrios como Puerto Madero, San Telmo y Villa Crespo presentan los precios más elevados, con montos que superan los $130.000 en promedio cada uno. 

Patrones Temporales:

▪ No se identificaron variaciones estacionales sginificativas en los precios, solo en Enero se muestra una leve caida, lo que indidiracia un demanda contantes durante el año.

Noches Mínimas:

▪ Existe una relación inversa entre la cantidad de noches mínimas requeridas y el precio promedio, es decir, siendo las estadías de 1 noche las más costosas ($113.920) seguidas por las estadias de 3 noches minimas ($83.000), este ultimo podria ser por el alquiler que se puede dar de un fin de semana entero (Viernes, Sabado y Domingo) elevando su precio. 
▪ Tanto las de 2, 4, 5 noches minnmas parecen no variar signfificativamente lo que indica precios similares. 

⚫ Dashboard ⚫
El dashboard final incluye:

Visualización de precios promedio por tipo de oferta

Cantidad de ofertas y Varaicion de precios por barrios. 

Gráficos temporales de variación de precios.

Tablas comparativas de precios según noches mínimas.

🔷 Conclusiones 🔷
Este análisis revela un mercado de alquileres temporales en Buenos Aires con claras segmentaciones por tipo de propiedad y ubicación geográfica. 

Los datos sugieren que:

Los anfitriones se volcarian a ofertar estadias de 1 noche o de 3 siendo las que mas ingresos pueden obtener.

Existen oportunidades de negocio en barrios con menor oferta y alta demanda. Barrios como Puerto Madero, San Telmo y Villa Crespo tiene precios elevados pero no lideran en ofertas, lo que podrian indicar que son barrios subexplotados. 

La flexibilidad en las noches mínimas podría ser un factor determinante en la competitividad de los listados. Las estadias de una noche son las mas caras lo que indicaria que los inquilinos buscan estadias cortas y pagan por ellas, se podrian hacer descuentos por estadias un poco mas largas con precio por debajo del promedio y asi ataraer a otro tipo de inquilinos.     


Tecnologías Utilizadas
Python (Pandas, NumPy) para limpieza y procesamiento de datos

Tableau para visualización y análisis interactivo



Archivos Incluidos
listings_limpio.csv: Dataset de listados después de la limpieza

calendar_limpio.csv: Dataset de calendario después de la limpieza

Limpieza de Datos.ipynb: Notebook con el proceso de limpieza y análisis

ReporteTableau.twb: Archivo de Tableau con las visualizaciones creadas


