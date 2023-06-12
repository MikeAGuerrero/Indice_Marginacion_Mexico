# El Índice de Marginalización en México

En el presente proyecto, se utilizará la Base de Datos "Índice de Marginación por Entidad Federativa y Municipio 2020" para llevar a cabo manipulaciones e implementar diversas transformaciones en los valores de las columnas. El propósito de esto es aprovechar dicha información y extraer conclusiones significativas que sean de utilidad para la formulación de nuevas estrategias socioeconómicas en el país, con el objetivo principal de lograr una notable disminución en el porcentaje de marginación.

## Bibliotecas Utilizadas

Implementamos las siguientes librerias en el desarrollo del proyecto:

- **Pandas**: Utilizada para la manipulación de datos en formato DataFrames
- **Numpy**: Nos ayudaba en las distintas operaciones matemáticas aplicadas a los distintos objetos
- **Matplotlib**: Libreria básica para la generación, manipulación y visualización de gráficas  
- **Scipy**: Utilizada para extraer la función de Correlación Lineal, *pearsonr*
- **Jupyter Notebook**: Todo el proyecto fue desarrollado en Jupyter Notebook

## Contenido del Proyecto


***Descripción del DataFrame***

Presentamos la gráfica en archivo *CVS* para poder describirla y hacer un rápido análisis de los valores cuantitativos que arroga la función *describe()* en los datos del DataFrame.

***Porcentaje de municipios por estados con índices de marginación (Municipio vs Marginación)***

Utilizando los valores del DataFrame de interés, proponemos dos maneras de graficar los valores. Nos quedaremos con un tipo de gráfico de barras apiladas y visualizaremos la relación que existe entre el porcentaje de Municipios VS Marginación.

***Municipio vs Marginación relativo a la población total de cada Estado***

Replicaremos el código utilizado para graficar el punto *3* , pero ahora con la modificación que tiene el valor de la población total del estado en nuestros resultados.

***Comparación de las gráficas Municipio vs Marginación***

Comparamos ambas gráficas colocándolas una al lado de la otra en la misma figura. Analizaremos cómo se relacionan y obtendremos nuestras primeras conclusiones significativas del proyecto.

***Correlación Lineal, Analfabetismo VS Indicadores***

Se graficaran con un *Scatter* el indicador de Analfabetismo en personas mayores a 15 años contra todos los demás Indicadores utilizados en este análisis. Después se utilizará la función de Correlación lineal para comparar los Indicadores contra el Analfabetismo y sacar nuestras últimas conclusiones significativas. 