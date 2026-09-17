# 🛒 RetailPro — Business Intelligence & Data Analytics

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC292B?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

Este repositorio contiene la solución integral de análisis de datos y Business Intelligence desarrollada para **RetailPro**, una empresa del sector comercial. Como **Analista de Datos**, estructuré el procesamiento de datos transaccionales, las consultas de negocio en SQL Server, el modelado analítico y la creación de tableros ejecutivos interactivos en Power BI.

---

## 📋 Tabla de Contenidos
- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Estructura del Repositorio](#-estructura-del-repositorio)
- [Instrucciones de Ejecución en SQL Server](#-instrucciones-de-ejecución-en-sql-server)
- [Visualización en Power BI](#-visualización-en-power-bi)
- [Autor](#-autor)

---

## 🔍 Descripción del Proyecto

El objetivo principal de este proyecto es transformar los registros de ventas de **RetailPro** en información valiosa para la toma de decisiones estratégicas. Entre los análisis realizados se destacan:
* Evaluación del **rendimiento mensual** y cálculo del ticket promedio.
* Identificación de los **productos más vendidos** y con mayor facturación.
* Segmentación de **clientes recurrentes** y patrones de consumo.
* Comparación de ventas mensuales frente a la **media anual** de facturación.

---

## 🛠️ Tecnologías Utilizadas

* **SQL Server:** Extracción, agregación, limpieza de datos y construcción de consultas analíticas complejas.
* **Power BI Desktop:** Diseños de dashboards interactivos, modelos relacionales en estrella/copo de nieve.
* **DAX (Data Analysis Expressions):** Creación de medidas calculadas, indicadores de rendimiento (KPIs) y análisis temporales (*Time Intelligence*).

---

## 📁 Estructura del Repositorio

```text
RetailPro/
│
├── 📁 sql/
│   ├── 01_esquema_y_limpieza.sql       # Creación de tablas y estructuración de datos
│   └── 02_consultas_y_metricas.sql     # Consultas analíticas y KPIs de negocio
│
└── 📁 powerbi/
    ├── RetailPro_Dashboard_Ventas.pbix  # Tablero ejecutivo de ventas y facturación
    └── RetailPro_Analisis_Clientes.pbix # Reporte de comportamiento y recurrencia de clientes
