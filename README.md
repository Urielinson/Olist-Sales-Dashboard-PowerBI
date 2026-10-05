# Dashboard de Ventas – E-commerce Olist (Power BI)

Dashboard interactivo sobre ~98 mil pedidos de un e-commerce brasileño (2016–2018).

![Dashboard](dashboard.png)

## Herramientas
Power BI (Power Query, modelo relacional, DAX) · Dataset: Brazilian E-Commerce Public Dataset by Olist (Kaggle)

## Proceso
- Limpieza en Power Query: tipos de datos, pedidos cancelados, traducción de categorías.
- Detecté y corregí un error de configuración regional que multiplicaba los precios por 100.
- Modelo relacional con tabla de calendario y medidas DAX (ventas, ticket promedio, participación Top 10).

## Hallazgos
1. Las ventas crecieron en 2017 y alcanzaron su pico en noviembre de 2017 (~R$1.0 M).
2. 10 de 72 categorías concentran el 62% de las ventas.
3. São Paulo genera el 38% de las ventas; SP, RJ y MG suman ~63%.

## Recomendaciones
- Reforzar inventario y promociones de las categorías líderes antes de noviembre.
- Evaluar acciones comerciales y logísticas para crecer fuera del sureste.

Nota: los datos de 2016 son escasos y 2018 termina en agosto, por lo que no se comparan años completos.
