# challange-data-science
🏪 Análisis de Desempeño de Tiendas — Proyecto Final
📖 Descripción general

Este proyecto tiene como propósito analizar el rendimiento de diferentes tiendas con el fin de determinar a cuál de ellas debería vender el Sr. Juan.
Para ello, se realizó un estudio de datos de ventas que incluye información sobre productos, categorías, precios, calificaciones de clientes y costos de envío.

El análisis se desarrolló utilizando Python y la biblioteca Pandas para el tratamiento de datos, y Matplotlib para la generación de visualizaciones que apoyan la toma de decisiones.

🎯 Objetivos del análisis

Calcular los ingresos totales de cada tienda.

Identificar las categorías de productos más y menos vendidas.

Evaluar las calificaciones promedio de los clientes por tienda.

Determinar los productos más y menos vendidos.

Analizar el costo de envío promedio en cada tienda.

Generar visualizaciones que permitan comprender los patrones encontrados.

Formular una recomendación final basada en datos objetivos.

🧮 Metodología

Se trabajó con un conjunto de datos que contiene las siguientes columnas principales:
Producto, Categoría, Precio, Costo de envío, Ciudad, Cantidad, Calificación.

A partir de estos datos se realizaron los siguientes pasos:

Paso	Descripción	Resultado principal
1	Cálculo de ingresos totales por tienda	Identificación de la tienda más rentable
2	Agrupación de productos por categoría	Detección de las categorías más vendidas
3	Promedio de calificaciones	Medición de la satisfacción de clientes
4	Identificación de productos más/menos vendidos	Determinación de tendencias de compra
5	Promedio de costo de envío	Evaluación de la eficiencia logística
6	Generación de gráficos	Visualización de resultados y patrones
📊 Visualizaciones generadas

Se crearon tres gráficos principales para ilustrar los resultados:

Gráfico de barras: Ingreso total por tienda

Gráfico apilado: Distribución de ventas por categoría y ciudad

Gráfico de líneas: Costo de envío promedio por tienda

Además, se generó un gráfico de dispersión opcional para analizar la relación entre ingresos y satisfacción del cliente.

🧠 Hallazgos clave

Cali registró el mayor ingreso total (757.500 MXN), aunque con baja satisfacción (1 estrella).

Medellín mostró ingresos altos (527.500 MXN) y excelente satisfacción (4.5 estrellas).

Bogotá tuvo ingresos moderados pero buenas valoraciones (4 estrellas).

Cartagena presentó menor volumen de ventas y baja satisfacción (1 estrella).

El costo de envío promedio fue más alto en Cali, lo que podría afectar la experiencia del cliente.

🏆 Conclusión y recomendación

Tras analizar todos los factores —ingresos, satisfacción del cliente, volumen de ventas y costos logísticos—, se recomienda que el Sr. Juan venda sus productos en la tienda de Medellín.

Justificación:

Combina buen nivel de ingresos con la mayor satisfacción del cliente (4.5).

Presenta categorías con alta rotación (especialmente muebles).

Mantiene costos de envío razonables en comparación con otras tiendas.

Su equilibrio entre rentabilidad y reputación la convierte en la mejor opción estratégica para asociarse.

🧰 Tecnologías utilizadas

Python 3.x

Pandas — análisis y manipulación de datos

Matplotlib — generación de gráficos

Google Colab / Jupyter Notebook — entorno de trabajo interactivo

📂 Estructura del proyecto
📁 proyecto_tiendas/
│
├── datos/
│   └── ventas_tiendas.csv
│
├── notebooks/
│   └── analisis_tiendas.ipynb
│
├── imagenes/
│   ├── ingresos_por_tienda.png
│   ├── categorias_por_tienda.png
│   └── costo_envio_promedio.png
│
└── README.md

✍️ Autor

Proyecto elaborado por:
brigitte sanhueza
📅 Fecha: 07 noviembre de 2025
💡 Análisis y visualizaciones desarrolladas en Google Colab
