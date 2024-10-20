EDA Report

1. Introducción
   Este informe presenta un análisis exploratorio de datos (EDA) realizado sobre el conjunto de datos Supermart Grocery Sales - Retail Analytics. El objetivo principal de este análisis es comprender mejor las ventas, los descuentos y las ganancias en relación con las categorías de productos y las regiones, así como identificar patrones y tendencias que puedan informar decisiones comerciales futuras.

2. Metodología
   El análisis se llevó a cabo en varias etapas:

Carga de Datos: Se importaron los datos desde el archivo CSV correspondiente.
Limpieza de Datos: Se realizaron diversas tareas de limpieza, que incluyeron la eliminación de duplicados, el manejo de valores nulos y la conversión de tipos de datos, asegurando que el conjunto de datos estuviera listo para el análisis.
Análisis Descriptivo: Se generaron estadísticas descriptivas para las variables numéricas (ventas, descuentos, ganancias) y se analizaron las variables categóricas (categoría de producto, nombre del cliente, ciudad, etc.).
Visualización de Datos: Se utilizaron histogramas, boxplots, matrices de correlación y gráficos de barras para visualizar las distribuciones y relaciones entre variables. 3. Resultados del Análisis
3.1 Análisis Descriptivo
Resumen de Ventas, Descuentos y Ganancias:
Ventas: Las ventas varían entre 500 y 2500 unidades, con un promedio de 1496.60 y una desviación estándar de 577.56.
Descuentos: Los descuentos oscilan entre el 10% y el 35%, con un promedio del 22.7%.
Ganancias: Las ganancias están entre 25.25 y 1120.95, con un promedio de 374.94.
3.2 Histogramas y Boxplots
Histograma de Ventas:
La distribución de las ventas es aproximadamente normal, con una mayor concentración entre 1500 y 2000 unidades. La curva de densidad confirmaría esta distribución de campana, indicando que hay poca variabilidad en las ventas.
Boxplot de Ventas:
La mediana de las ventas se sitúa alrededor de 1500 unidades. La caja presenta una dispersión moderada y no se observan outliers, sugiriendo que los datos son confiables y no presentan valores extremos.
3.3 Matriz de Correlación
Sales vs. Discount: Correlación cercana a 0 (-0.01), indicando que los descuentos no afectan significativamente las ventas.
Sales vs. Profit: Correlación positiva moderada (0.61), lo que sugiere que a medida que aumentan las ventas, también lo hacen las ganancias.
Discount vs. Profit: Correlación negativa fuerte (-0.8), indicando que mayores descuentos tienden a reducir las ganancias.
3.4 Gráfico de Barras de Categorías de Productos
Frecuencia de Categorías: Se observó una desigualdad en la frecuencia de las diferentes categorías de productos. Las categorías más populares son "Snacks", "Eggs, Meat & Fish", y "Bakery", mientras que "Oil & Masala" y "Beverages" tienen una menor demanda. 4. Conclusiones
Concentración de Ventas: La mayoría de las ventas se concentran en un rango relativamente estrecho alrededor de la mediana, sugiriendo un comportamiento de compra predecible.
Descuentos y Ventas: Los descuentos no parecen tener un impacto significativo en el volumen de ventas, lo que podría indicar la necesidad de reevaluar las estrategias de precios.
Relación entre Ventas y Beneficios: Existe una relación positiva entre las ventas y las ganancias, sugiriendo que se pueden implementar estrategias para aumentar las ventas sin depender únicamente de descuentos.
Enfoque en Categorías Populares: Las categorías con mayor frecuencia podrían ser el foco de futuras campañas de marketing y promociones para maximizar el potencial de ventas. 5. Recomendaciones
Reevaluar Estrategias de Descuento: Dada la relación inversa entre descuentos y beneficios, se recomienda explorar otras formas de incentivar las ventas sin comprometer el margen de ganancia.
Aprovechar Categorías Populares: Se sugiere centrar esfuerzos de marketing en las categorías de productos más vendidas para maximizar el retorno de inversión.
Monitorear Otras Variables: Se recomienda realizar un análisis más profundo de otros factores que podrían influir en las ventas y la rentabilidad, como la calidad del servicio al cliente y las tendencias del mercado
