# Alura_Store_Latam
Primer desafio
Nombre: Proyecto-Sr-Juan
Descripción: Análisis de ventas para determinar en qué tienda debería vender el Sr. Juan.
Tecnologías: Python, Pandas, Matplotlib, Google Colab

#Propósito del Análisis
El objetivo principal de este análisis fue determinar en qué tienda le conviene vender sus productos al Sr. Juan, comparando el desempeño de cuatro tiendas distintas.

Para ello, se evaluaron:
-Ingresos totales generados por cada tienda.
-Categorías de productos más y menos vendidas.
-Calificaciones promedio otorgadas por los clientes.
-Productos destacados (más vendidos y menos vendidos).
-Costo de envío promedio asumido por los clientes.
-Patrones geográficos de venta, utilizando latitud y longitud para identificar zonas con mayor actividad comercial.
-Este análisis permite tomar una decisión estratégica, optimizando las posibilidades de rentabilidad y satisfacción del cliente.

#Estructura del Proyecto
Proyecto-Sr-Juan/
│
├── data/                      # Archivos de datos utilizados (CSV o XLSX)
│   └── ventas.csv
│
├── notebook/                  # Análisis principal
│   └── analisis_ventas.ipynb
│
├── resultados/                # Gráficos e imágenes exportadas
│   ├── ingresos_por_tienda.png
│   ├── categorias_tienda_barras.png
│   ├── calificacion_promedio_torta.png
│   └── mapa_geografico_ventas.html (si usaste folium)
│
└── README.md                  # Documentación del proyecto


| Gráfico                                          | Descripción                                       | Insight Clave                                                                                        |
| ------------------------------------------------ | ------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Barras – Ingresos por tienda**                 | Comparación directa del total vendido por tienda. | La Tienda 1 presenta el mayor ingreso total, aunque la diferencia respecto a la Tienda 2 es pequeña. |
| **Torta – Calificación promedio**                | Representa la satisfacción del cliente.           | La Tienda 3 obtiene la mejor valoración promedio, lo que sugiere mayor satisfacción post-compra.     |
| **Barras Horizontales – Productos más vendidos** | Identifica qué productos dominan en ventas.       | Algunas tiendas concentran ventas en pocas categorías, otras muestran mayor diversidad.              |
| **Mapa de Dispersión de Ventas (lat, lon)**      | Muestra la ubicación geográfica de las compras.   | Las tiendas presentan zonas de mayor actividad que pueden influir en la logística y costos.          |


#Ejecución del análisis
Instrucciones para Ejecutar el Notebook
Requisitos: Python 3.x
pip install pandas matplotlib seaborn folium

1.Clona este repositorio: git clone <URL_DEL_REPOSITORIO>
2.Entra en la carpeta: cd Proyecto-Sr-Juan/notebook
3.abre el notebook: jupyter notebook analisis_ventas.ipynb
4.Ejecuta las celdas en orden.











