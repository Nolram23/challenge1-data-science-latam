📊 Alura Store - Análisis de Tiendas
Este proyecto tiene como objetivo analizar el comportamiento de 4 tiendas de un cliente utilizando Python y gráficos interactivos en Google Colab. El análisis busca identificar cuál de las tiendas presenta un desempeño más bajo y podría ser considerada para cierre, con base en datos históricos de ventas, visitas y otros KPIs.

🎯 Propósito del Análisis
Evaluar el rendimiento individual de cada tienda.

Identificar tendencias de ventas, estacionalidades y niveles de productividad.

Tomar decisiones basadas en datos sobre cuál tienda cerrar para optimizar recursos.

🗂️ Estructura del Proyecto
bash
Copiar
Editar
AluraStore/
│
├── AluraStore_Analisis.ipynb        # Notebook principal del análisis
├── data/
│   └── ventas_tiendas.csv           # Archivo con los datos de ventas por tienda
├── images/
│   └── grafico_ventas_mensuales.png
│   └── comparativa_kpis_tiendas.png
├── README.md                        # Documentación del proyecto
📈 Ejemplos de Gráficos e Insights
🔹 Ventas Mensuales por Tienda
Gráfico de líneas que muestra la evolución mensual de ventas por tienda. Se observaron caídas significativas en la Tienda 3 durante el segundo semestre.


🔹 Comparativa de KPIs por Tienda
Gráfico de barras comparando visitas, tasa de conversión y ticket promedio. La Tienda 2 tuvo el ticket promedio más bajo y la menor conversión.


📌 Insight Principal
La Tienda 2 muestra un bajo desempeño sostenido en todos los indicadores clave, por lo que se sugiere considerarla como candidata para cierre.

▶️ Instrucciones para Ejecutar el Notebook
Abre el siguiente enlace para acceder al notebook en Google Colab:
👉 Abrir en Colab

Asegúrate de subir el archivo ventas_tiendas.csv a la sesión de Colab o monta tu Google Drive.

Ejecuta las celdas en orden, asegurándote de instalar las bibliotecas necesarias:

python
Copiar
Editar
!pip install pandas matplotlib seaborn
Observa los gráficos generados y lee los análisis explicativos para comprender mejor el rendimiento de cada tienda.

🧠 Tecnologías Utilizadas
Python 3

Pandas

Matplotlib

Seaborn

Google Colab

