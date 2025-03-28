# Reboot-Academy - Proyecto 1 - Analisis de Ventas (Retail)

## Guión Análisis de Ventas (Retail)
.CSV: https://docs.google.com/spreadsheets/d/1Ws6i39c9i5r9aB-5UcIc7W3nwz8JJeFqHUGrkZ8g-5w/edit?gid=796607011#gid=796607011  
GUIA: https://docs.google.com/document/d/13h75QlGcxcgz-OEpH39CxoKPFDl_XFy8/edit  
Documentacion proyecto: https://docs.google.com/document/d/1NO3km4OiGzOv3w4OVONZHamDEUgKUzkJtdryy8l9rJQ/edit?tab=t.0  

### CONTEXTO
Una cadena de distribución de productos de oficina, tecnología y mobiliario desea analizar su histórico de ventas. La base de datos contiene detalles sobre pedidos individuales: cliente, producto, fecha, categoría, segmento, modo de envío, localización y valor de la venta.

### SOLICITUD DEL CLIENTE

“Queremos identificar patrones relevantes que nos ayuden a optimizar nuestras estrategias de ventas y mejorar la segmentación de clientes y productos.”

- Analizar los productos más vendidos.
- Detectar estacionalidades o tendencias temporales en las ventas.
- Analizar las ventas por segmento de cliente, región y modo de envío.
- Proponer al menos dos recomendaciones prácticas basadas en los hallazgos.

# DIA 1 - 24/03/2025

- Hoja de ruta:
    * Creación de repo en Github.  
    * Planificación del proyecto y creación de plantilla kanban de tareas.
    * 
- Recolección y Preparación de Datos 

## Importar y entender el dataset (.csv)

- Cargar el archivo en Google Sheets.
- Explorar las dimensiones, tipos de datos y estructura.

## Data Profiling

- Identificar valores nulos, duplicados e inconsistencias.
- Analizar distribuciones de variables clave.
- Verificar formatos de fechas, nombres, categorías, etc.

## Limpiezade Datos

- Manejo de valores nulos (imputación o eliminación).
- Eliminación de duplicados.
- Estandarización de nombres de productos, regiones y categorías.
- Corrección de formatos (ej., fechas, moneda, números).

## BLOQUEOS:
- Order ID: Celdas en blanco no se pueden inputar. ¿Que hacemos con ellas?
- Fechas: Problemas con la configuracion regional para que el sheet detecte la fecha en formato europeo.
- PRoblema para imputar ciertos campos. Solución: Usar función VLOOKUP.
- FIlas duplicadas (cifra inicial de 992), que suponen el 8.80% del total de datos. ¿Que hacemos?
 
# DIA 2 - 25/03/2025

Daily brief: Guillermo

## Limpiezade Datos (continuación, mañana)

- Manejo de valores nulos (imputación o eliminación).
- Eliminación de filas donde todos los valores están duplicados: 1183 filas eliminadas

## Análisis Exploratorio de Datos (EDA)

✅ Análisis de productos más vendidos

    Identificar los productos con mayores ventas en unidades y en ingresos.

    Analizar la contribución de cada categoría de productos.

✅ Detección de tendencias estacionales

    Analizar patrones de ventas por mes, trimestre y año.

    Evaluar si existen aumentos en fechas específicas (ej., Black Friday, Navidad).

✅ Análisis de ventas por cliente, región y modo de envío

    Segmentar clientes según frecuencia de compra, ticket promedio y total gastado.

    Identificar las regiones con mayor volumen de ventas.

    Analizar la distribución de ventas por método de envío y tiempos de entrega.

✅ Generación de visualizaciones preliminares

    Histogramas, boxplots y gráficos de barras para entender las distribuciones.

    Líneas de tiempo para tendencias estacionales.

# DIA 3 - 26/03/2025

Daily brief: Mahalia

3️⃣ Creación del Dashboard en Looker Studio

✅ Conectar la fuente de datos

    Importar el dataset limpio a Looker Studio.

    Definir métricas clave (KPI) y dimensiones relevantes.

✅ Construcción de visualizaciones

    Gráficos de ventas por categoría de producto.

    Línea de tendencia de ventas por fecha.

    Segmentación de clientes por ticket promedio y frecuencia.

    Mapa de calor de ventas por región.

    Comparación de métodos de envío y tiempos de entrega.

✅ Interactividad

    Filtros por fecha, región, cliente y categoría de producto.

# DIA 4 - 27/03/2025

Daily brief: Sindy

✅ Construcción de visualizaciones (Continuación).

    Organización de gráficas del Dashboard en base a criterios acordados.

4️⃣ Creación de la Presentación en Canva

✅ Resumen del proyecto

    Objetivo y preguntas de negocio a responder.

✅ Hallazgos clave

    Presentar insights con gráficos claros y explicaciones.

✅ Recomendaciones

    Proponer al menos 2 estrategias prácticas basadas en los datos.

    Justificar con evidencia de las visualizaciones.

✅ Conclusión

    Síntesis de los hallazgos y próximos pasos.

# DIA 5 - 28/03/2025

Daily brief: Ricardo

5️⃣ FInalizacion y ensayo de la presentación con CANVA.

✅ Revisión y refinamiento

    Ajustar insights y gráficos con base en la retroalimentación del equipo.

    Validar que el dashboard sea interactivo y claro.

✅ 

    Explicar los insights y recomendaciones de manera clara y enfocada.
