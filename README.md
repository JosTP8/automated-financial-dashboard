# 📊 Automated Financial Dashboard – Global Superstore
**Portafolio Data Analyst | 2025**  
Automatización de KPIs financieros con Python + Dashboard en Power BI

---

## 🎯 1. Objetivo del proyecto
Construir un **dashboard financiero automatizado** que procese datos de ventas globales y genere indicadores clave de negocio:

- Ventas  
- Utilidad  
- Margen  
- Desempeño por producto, categoría y segmento  
- Análisis por país y región  
- Tendencias temporales  

El objetivo es simular un flujo empresarial real: **ETL en Python + visualización ejecutiva en Power BI**.

---

## 📁 2. Dataset: Global Superstore
Se utilizó la base de datos **Global Superstore**, ampliamente usada en proyectos de Business Intelligence.

Incluye variables como:

- 📦 Product Name, Category, Sub-Category  
- 👤 Segment, Customer ID  
- 🌍 Country, Region  
- 🛒 Order ID, Order Date  
- 💰 Sales, Profit, Quantity, Discount  

---

## 🛠️ 3. Herramientas utilizadas
- 🐍 **Python** (Pandas, NumPy) — Limpieza y preprocesamiento  
- 📓 **Jupyter Notebook**  
- 📊 **Power BI Desktop** — Dashboard final  
- 🗂 **GitHub**  

---

## 🔎 4. Proceso analítico

### 🧹 4.1 Limpieza y preparación
- Eliminación de valores nulos  
- Conversión de fechas  
- Creación de columnas derivadas (Year, Month, Profit-Rate)  
- Validación de tipos numéricos  

### 🔄 4.2 Automatización del flujo
El notebook ejecuta un proceso tipo ETL:

1. **Carga automática** del archivo Global Superstore  
2. **Procesamiento y normalización** de columnas  
3. **Generación de KPIs**  
4. **Exportación del dataset limpio** para Power BI  

### 📈 4.3 KPIs generados
- Total Sales  
- Total Profit  
- Profit Rate  
- Sales vs Profit por categoría  
- Segment Performance  
- Países más rentables  
- Productos con mayor margen  

### 📊 4.4 Dashboard en Power BI
Incluye visualizaciones sobre:

- Ventas y Utilidad global  
- Mapa por país  
- Profit por Categoría/Sub-Categoría  
- Tendencia de ventas mensual  
- Top 10 productos más rentables  
- Segment comparison  
- KPI cards automáticas  

---

## 📌 5. Principales hallazgos
- 📈 **Tecnología y Oficina** destacan por mayor volumen de ventas.  
- 💰 **Furniture** muestra utilidad baja o negativa en algunos países.  
- 🌍 **United States, India y China** concentran gran parte de las ventas globales.  
- 📦 Algunos productos presentan pérdidas por descuentos altos.  
- 🔍 Varias regiones muestran crecimiento sostenido mes a mes.

---

## 💡 6. Insights accionables
- Reducir descuentos en categorías con margen bajo.  
- Reforzar estrategias en mercados con alta rentabilidad (EE.UU., India).  
- Revisar productos con utilidad negativa para ajustes de pricing.  
- Incentivar ventas en segmentos con alto ROI.  
- Diagnosticar causas de baja utilidad en categorías específicas.

---

## 📊 7. Dashboard
Archivo en el repositorio:  
`Dashboard financiero automatizado.pdf`

---

## 📂 8. Estructura del repositorio
├── 05_financial_dashboard_automation.ipynb
├── Global_Superstore.xlsx
├── Dashboard_financiero_automatizado.pdf
└── README.md

---

## 👤 9. Autor
**Josué Téllez**  
Data Analyst — Portafolio 2025
