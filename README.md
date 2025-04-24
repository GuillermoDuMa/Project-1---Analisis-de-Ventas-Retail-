# Reboot-Academy - Proyecto 1 - Analisis de Ventas (Retail)

Proyecto realizado por: @GuillermoDuMa, @MahaliaYM, @Rarvelom, @Sindy138

## Recursos 

- **.CSV:** https://docs.google.com/spreadsheets/d/1Ws6i39c9i5r9aB-5UcIc7W3nwz8JJeFqHUGrkZ8g-5w/edit?gid=796607011#gid=796607011  
- **GUIA:** https://docs.google.com/document/d/13h75QlGcxcgz-OEpH39CxoKPFDl_XFy8/edit  
- **Documentacion proyecto:** https://docs.google.com/document/d/1NO3km4OiGzOv3w4OVONZHamDEUgKUzkJtdryy8l9rJQ/edit?tab=t.0
- **Looker Studio Dashboard** https://lookerstudio.google.com/reporting/0dbdd5a2-16f0-4373-b14c-82d1493ffb49  
- **CANVA presentación:** https://www.canva.com/design/DAGivERvta8/gUROBhEPa47AyBdGd55U3A/edit

## Guión Análisis de Ventas (Retail)


### CONTEXTO
Una cadena de distribución de productos de oficina, tecnología y mobiliario desea analizar su histórico de ventas. La base de datos contiene detalles sobre pedidos individuales: cliente, producto, fecha, categoría, segmento, modo de envío, localización y valor de la venta.

### SOLICITUD DEL CLIENTE

“Queremos identificar patrones relevantes que nos ayuden a optimizar nuestras estrategias de ventas y mejorar la segmentación de clientes y productos.”

- Analizar los productos más vendidos.
- Detectar estacionalidades o tendencias temporales en las ventas.
- Analizar las ventas por segmento de cliente, región y modo de envío.
- Proponer al menos dos recomendaciones prácticas basadas en los hallazgos.

### Hoja de ruta:
- Creación de repo en Github.
- Planificación del proyecto y creación de plantilla kanban de tareas.
- Recolección y Preparación de Datos 

## Importación y primer vistazo del dataset (.csv)

- Cargar el archivo en Google Sheets.
- Reparto de datos al equipo para su revisión.

## Perfilado de datos (Data Profiling)

- Explorar las dimensiones, tipos de datos y estructura.
- Identificar valores nulos, duplicados e inconsistencias de formato.
- Analizar distribucion de variables clave con uso de gráficas y XLMiner.
- Verificar formatos de fechas, nombres, categorías, etc.

## Limpiezade Datos

- Manejo de valores nulos (imputación o eliminación).
- Eliminación de duplicados.
- Estandarización de nombres de productos, regiones y categorías.
- Corrección de formatos (ej., fechas, moneda, números).
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

5️⃣ FInalizacion y ensayo de la presentación con CANVA.

✅ Revisión y refinamiento

    Ajustar insights y gráficos con base en la retroalimentación del equipo.

    Validar que el dashboard sea interactivo y claro.

✅ 

    Explicar los insights y recomendaciones de manera clara y enfocada.

## BLOQUEOS:
- Fechas: Problemas con la configuracion regional para que el sheet detecte la fecha en formato europeo.  
- Sales: Formato para decimales de cara a estandarizar valores. ¿Formato europeo o americano?  
