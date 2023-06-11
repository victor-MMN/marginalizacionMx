# El índice de marginalización de México

En este proyecto exploraremos un poco un estudio multidimensional de la pobreza, el cual consiste en indicadores sociodemográficos e índice de marginación del territorio mexicano. Este estudio lo realizó el Consejo Nacional de Población (CONAPO) del gobierno mexicano, se realiza cada 5 años. El que usaremos en esta ocasión es el de 2020.

Los datos se encuentran en la página [Índices de marginación 2020 del gobierno Méxicano](https://www.gob.mx/conapo/documentos/indices-de-marginacion-2020-284372). Descargado el **9 de junio del 2023**. 

El archivo a descargar es **Base de datos por municipio 2020**. Al descargarlo obtendras un archivo excel **IMM_2020.xls** que constará de 3 hojas, la segunda (IMM_2020) tendrá los datos para extraerse y la tercera (diccionario) es el diccionario de variables, el mismo que se presenta a continuación


### Diccionario de variables

CVE_ENT  : Clave de entidad federativa

NOM_ENT	 : Nombre de entidad federativa

CVE_MUN	 : Clave del municipio

NOM_MUN	 : Nombre del municipio

POB_TOT	 : Población total

ANALF	 : Porcentaje de población analfabeta de 15 años o más

SBASC	 : Porcentaje de población de 15 años o más sin educación básica

OVSDE	 : Porcentaje de ocupantes en viviendas particulares habitadas sin drenaje ni excusado

OVSEE	 : Porcentaje de ocupantes en viviendas particulares habitadas sin energía eléctrica

OVSAE	 : Porcentaje de ocupantes en viviendas particulares habitadas sin agua entubada

OVPT	 : Porcentaje de ocupantes en viviendas particulares habitadas con piso de tierra

VHAC	 : Porcentaje de viviendas particulares con hacinamiento

PL.5000	 : Porcentaje de población que vive en localidades menores a 5 000 habitantes

PO2SM	 : Porcentaje de población ocupada con ingresos de hasta 2 salarios mínimos

IM_2020	 : Índice de marginación, 2020

GM_2020	 : Grado de marginación, 2020

IMN_2020 : Índice de marginación normalizado, 2020

Todo el análisis se muestra en el archivo **estudioMarginacion.ipynb**. Por último, la siguiente gráfica muestra un poco la exploración que se hizo. En la gráfica vemos el porcentaje de la población, respecto a la población total de cada estado, con grado de marginación "muy bajo", "bajo", "medio", "alto" y "muy alto".

<div style="text-align:center">
  <img src="https://github.com/victor-MMN/marginalizacionMx/blob/main/porcentGMporPobPorEstado.jpg" width="900" height="500" alt="grado de marginación porcentual por población en cada estado mexicano">
</div>
