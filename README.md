# Presupuestos_Legislativos_2020-2021 
 Comparación de presupuestos legislativos por congreso para el periodo 2020-2021.
 
 Aclaraciones:
- Para este proyecto se utilizó XLConnect, un paquete que funciona con rjava, una interfaz de bajo nivel de Java para R. En caso de no tenerlo instalado, es necesario hacerlo y descargar una versión adecuada al sistema operativo, para vincularla a R. De otra forma, no puede funcionar el paquete.

- La base de datos se encuentra en formato xlsx debido a que contiene encabezados en celdas combinadas y centradas, lo que dificulta la lectura o una conversión correcta a csv. Creé una hoja con columnas y encabezados simples para leer los datos empleados en el análisis, pero conservé las demás hojas con los datos para propósitos ilustrativos.

- En caso de no contar con XLConnect, existen otras opciones como openxl, readr y otros paquetes para la lectura de datos, siempre y cuando se tengan en consideración las características ya mencionadas del libro de Excel.
