# 📊 Telecom X — Análisis de Evasión de Clientes (Churn)

Este repositorio contiene el análisis exploratorio de datos (**EDA**) y tratamiento inicial de un dataset de la empresa ficticia **Telecom X**, que enfrenta una alta tasa de cancelaciones de clientes (**Churn**).  
El trabajo se realizó en **Python** y está diseñado para ejecutarse en **Google Colab**.

## 📌 Objetivo
Analizar el comportamiento de los clientes y encontrar patrones asociados a la cancelación del servicio, con el fin de generar insights y recomendaciones estratégicas que reduzcan el churn.

## 🛠 Tecnologías y Librerías Utilizadas
- **Python 3.x**
- **pandas** — Manipulación y análisis de datos
- **numpy** — Operaciones numéricas
- **matplotlib** — Visualización de datos
- **requests** — Consumo de datos desde API/URL
- **nbformat** — Generación del notebook

## 📂 Estructura del Repositorio

## 📥 Dataset
El dataset utilizado proviene de un archivo JSON disponible en GitHub:  
[TelecomX_Data.json](https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json)  

Se carga directamente desde su **raw URL** para facilitar la ejecución en Colab.

## 🔍 Contenido del Notebook
1. **Introducción** — Contexto del problema y objetivos del análisis.
2. **ETL (Extracción, Transformación y Carga)** — Limpieza de datos, estandarización de columnas, tratamiento de valores faltantes.
3. **EDA (Análisis Exploratorio de Datos)** —  
   - Tasa de churn global  
   - Distribución por variables categóricas (tipo de contrato, método de pago, etc.)  
   - Análisis de variables numéricas (tenure, monthly charges, total charges)  
   - Correlaciones con churn
4. **Conclusiones e Insights** — Principales hallazgos.
5. **Recomendaciones** — Estrategias para reducir la evasión.

## 🚀 Ejecución en Google Colab
1. Abre el siguiente enlace en Colab (una vez que el repo esté en GitHub):
2. Ejecuta las celdas en orden.
3. Analiza los gráficos y outputs generados.

## 📊 Ejemplo de Resultados
- **Tasa de churn** calculada automáticamente.
- Identificación de **segmentos de alto riesgo** (contratos mes a mes, pagos electrónicos).
- Variables numéricas con mayor correlación al churn.

## 📜 Licencia
Este proyecto es de uso educativo y se distribuye bajo la licencia MIT.

---
💡 **Nota:** Este análisis es una base para desarrollar modelos predictivos de churn usando machine learning.
