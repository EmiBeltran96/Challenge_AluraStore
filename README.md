# Desafío: Análisis de Datos de Alura Store

### Introducción
Este proyecto fue desarrollado como parte de un desafío para analizar los datos de ventas de una cadena de tiendas ficticia, Alura Store. El objetivo principal es ayudar al dueño, el Sr. Juan, a identificar la tienda menos eficiente de sus cuatro sucursales para que pueda tomar la decisión de venderla y reinvertir en un nuevo emprendimiento.

### Metodología
Para este análisis, se utilizó un conjunto de datos en formato CSV que contiene información sobre ventas, productos, calificaciones de clientes y costos de envío de las cuatro tiendas.

Las principales herramientas utilizadas fueron:
-   **Pandas:** Para la carga, manipulación y análisis de los datos.
-   **Matplotlib:** Para la visualización de los resultados a través de gráficos.
-   **Google Colab:** Como entorno de desarrollo para ejecutar el código.

### Análisis y Resultados
Se realizaron varios análisis para evaluar el rendimiento de cada tienda:
1.  **Ingresos Totales:** Se calculó la suma de todos los precios de venta para determinar el ingreso total de cada tienda.
    -   *Resultado:* La Tienda 4 tuvo el ingreso más bajo.
2.  **Ventas por Categoría:** Se identificaron las categorías de productos más y menos vendidas en cada tienda.
    -   *Resultado:* Todas las tiendas tienen un rendimiento similar en categorías populares como 'Muebles' y 'Electrónicos'.
3.  **Calificación Promedio:** Se calculó la satisfacción del cliente a través de la calificación promedio.
    -   *Resultado:* La Tienda 1 obtuvo la calificación promedio más baja.
4.  **Costos de Envío:** Se analizó el costo de envío promedio por tienda para entender su impacto en la rentabilidad.
    -   *Resultado:* La Tienda 1 tuvo el costo de envío más alto.

### Conclusión y Recomendación Final
Basado en un análisis completo de los datos, mi recomendación al Sr. Juan es **vender la Tienda 4**.

Aunque la Tienda 1 tiene la calificación de clientes más baja, la Tienda 4 es la que presenta la debilidad más crítica: **es la que genera el menor ingreso total**. Un bajo rendimiento financiero es el factor más importante a considerar, ya que afecta directamente la viabilidad del negocio.

### Cómo utilizar este proyecto
El proyecto está desarrollado en un notebook de Google Colab. Para ejecutar el código y reproducir el análisis, siga estos pasos:
1.  Abra el archivo `AluraStoreLatam (2).ipynb` en Google Colab.
2.  Ejecute cada celda de código en orden.
3.  Los resultados numéricos y los gráficos se mostrarán en la salida de cada celda.
