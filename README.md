Estudio de Operaciones Aéreas en España - 2024 

Este proyecto pretende realizar un análisis sobre las operaciones aéreas de los distintos aeropuertos españoles durante el ejercicio de 2024, identificando patrones temporales por aeropuerto para poder predecir las necesidades y volumen de trabajo en las distintas bases tales como personal de apoyo en aeropuertos, procedencia de los distintos pasajeros, etc.

Estructura del proyecto:
-	“Operaciones por Compañía -base de datos original”: base de datos original descargada de la web de aena (https://www.aena.es/es/estadisticas/consultas-personalizadas.html).
-	“Operaciones por Compañía – dashboard”: archivo con la base de datos pulida, tablas dinámicas y Dashboard final.
-	“Read me”: descripción del proyecto.

Transformación y limpieza de los datos.
-	Crear una nueva pestaña para “crear” una base de datos más limpia con unos datos en un formato más pulido con el que poder trabajar:
o	Rellenar celdas en blanco de las columnas A-F
o	Modificar el formato de la fecha para poder trabajar con ellas y que Excel las identifique como tales.
o	Identificación de la información que necesitamos usar para nuestro análisis.
	Entendemos que, según la información del reporte, aquellas filas con “Operaciones Totales” = 0, no se han llegado a producir, por lo que se pueden eliminar de nuestra base de datos.

Resultados y conclusiones:
-	Observamos cierta estacionalidad durante los meses de junio, julio y agosto, siendo julio el mes con mayor actividad aérea, situándose significativamente por encima de la media del resto de meses.
-	Los 5 destinos más frecuentados, suman un total de 1.976.223 vuelos, lo que supone un 76% del total de vuelos con salida desde aeropuertos españoles, siendo España el destino más frecuente, con un peso del 48%.
-	Analizando el top 5 de compañías, vemos que la compañía con mayor número de vuelos es Ryanair, seguida de cuatro compañías españolas.
-	Adolfo Suárez Madrid-Barajas encabeza la lista de operaciones, seguido por Barcelona-El Prat. El resto de los aeropuertos presenta cifras considerablemente más bajas, destacando una alta concentración del tráfico en estas dos principales bases. Dependiendo del mes que queramos analizar, vemos que el resto de los aeropuertos varían su posición, pero los dos principales se mantienen siempre en los primeros puestos de la lista.

Próximos pasos:
-	Comparar los resultados con estudios de años anteriores para ver si las tendencias son siempre las mismas o hay alguna variación. En caso de que las tendencias no sigan la misma línea año tras año, habría que indagar en ello para entender dichas diferencias (festivos, eventos específicos ocurridos en un año concreto, situaciones sociales como crisis económicas que puedan alterar la tendencia, etc.).
-	En caso de querer seguir con el análisis, sería interesante realizar un estudio más específico por aeropuerto para adaptarse a las necesidades de cada uno.

Autor:
Beatriz Banegas
