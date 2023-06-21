
# Sales Analysis
Utilizamos las bibliotecas Python Pandas y Matplotlib para analizar y responder consultas comerciales sobre un conjunto de datos de ventas de 12 meses. Estos datos contienen registros detallados de cientos de miles de compras realizadas en tiendas de electrónica, incluyendo información sobre el mes de compra, tipo de producto, costo de compra, dirección de entrega, entre otros. Con Pandas, podemos manipular y analizar estos datos, mientras que Matplotlib nos permite visualizar los resultados.


Empezamos por limpiar nuestros datos. Las tareas durante esta sección incluyen:
- Soltar valores NaN de DataFrame
- Eliminación de filas en función de una condición.
- Cambiar el tipo de columnas (to_numeric, to_datetime, astype)

Una vez que hemos limpiado un poco nuestros datos, movemos la sección de exploración de datos. En esta sección exploramos 5 preguntas comerciales de alto nivel relacionadas con nuestros datos:
- ¿Cuál fue el mejor mes para las ventas? ¿Cuánto se ganó ese mes?
- ¿Qué ciudad vendió más producto?
- ¿A qué hora debemos mostrar anuncios para maximizar la probabilidad de que el cliente compre el producto?
- ¿Qué productos se venden juntos con mayor frecuencia?
- ¿Qué producto vendió más? ¿Por qué crees que vendió más?

Para responder a estas preguntas, analizamos muchos métodos diferentes de pandas y matplotlib. Incluyen:
- Concatenar varios csv para crear un nuevo DataFrame (pd.concat)
- Adición de columnas
- Análisis de celdas como cadenas para crear nuevas columnas (.str)
- Usando el método .apply()
- Uso de groupby para realizar análisis agregados
- Trazado de gráficos de barras y gráficos de líneas para visualizar nuestros resultados
- Etiquetar nuestras gráficas