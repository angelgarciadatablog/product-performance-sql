# Product Performance Insights – Análisis del rendimiento de productos en un ecommerce

Este proyecto analiza el rendimiento de productos de un ecommerce a través de eventos de conversión registrados en Google Analytics 4.

Se exploran métricas como vistas de producto, agregados al carrito, inicios de checkout y compras, todas obtenidas desde BigQuery.

A partir de estos datos, se construye una vista unificada que permite obtener insights a nivel de producto y categoría, 
con el objetivo de optimizar decisiones comerciales basadas en comportamiento real de los usuarios.

## 📍 Pregunta principal del Negocio
¿Los productos más vistos son los que generan mayores ingresos?


## 🎯 Objetivo del proyecto
1. **Evaluar el ciclo completo del producto**: desde las vistas, agregados al carrito, inicios de checkout y compras (eventos de GA4)

2. **Medir la eficiencia de productos**: comparando el volumen de visualizaciones con las ventas para detectar productos con alta exposición pero baja conversión.

3. **Generar insights accionables**: por producto y por categoría, que permitan mejorar decisiones comerciales, ajustar estrategias de marketing y priorizar productos según su rentabilidad y comportamiento real.


## 🛠️ Herramientas y tecnologías

- **BigQuery** – Almacenamiento y análisis de grandes volúmenes de datos.
- **SQL** – Extracción y manipulación de datos.
- **Google Analytics 4** – Métricas de comportamiento de usuarios.
- **Looker Studio** – Visualización de reporte

## 🗂️ Estructura del proyecto
```plaintext
ecommerce-performance-insights/       # Descripción general del proyecto integral
├── README.md                         
├── 1-product-performance-insight/    
│   ├── README.md                     # Descripción general del módulo
│   ├── analysis/                     # Desarrollo, lógica y hallazgos
│   ├── queries/                      # Consultas SQL
│   ├── images/                       # Soporte visual
│   └── dashboard/                    # Archivos relacionados a visualización interactiva
```


## 📈 Resultados esperados

- Obtener una visión 360° del rendimiento de cada producto evaluando los eventos de conversión (vistas, carritos, checkouts y compras).
- Detectar productos con alto interés pero baja conversión, proponiendo acciones correctivas como cambios de precio, promociones o mejoras en la ficha de producto.
- Identificar oportunidades por categoría, priorizando productos con alto potencial de conversión y rotación.


## 📓 Análisis detallado 

El análisis completo se encuentra en el archivo [`product-performance-insight-analysis.md`](analysis/product-performance-insight-analysis.md) donde se explican paso a paso las consultas realizadas, los datos integrados y las conclusiones extraídas.

## 📈 Dashboard Interactivo

Consulta el dashboard interactivo desarrollado en Looker Studio:  
🔗 [Ver en línea](https://lookerstudio.google.com/reporting/5e8d97c8-e7c4-4c62-93f5-0d7396d216d7)

> Este dashboard permite visualizar el funnel de conversión por producto, analizar patrones de comportamiento y tomar decisiones con base en los datos de GA4 procesados en BigQuery.


## 👤 Autor

**Angel García**  
Analista de Datos | Lima, Perú  
👤 Perfil profesional: 🔗 [LinkedIn](https://www.linkedin.com/in/angelgarciachanga)  
🎥 Canal educativo: [@angelgarciadatablog](https://youtube.com/@angelgarciadatablog)  
💼 Especializado en Power BI, SQL y análisis de campañas de marketing.  


