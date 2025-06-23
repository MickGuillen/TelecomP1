# 📊 Análisis de Datos de Clientes – Telecomunicaciones

Este repositorio contiene un proyecto desarrollado en Python, enfocado en el análisis preliminar de datos de clientes de una empresa de telecomunicaciones. A partir de un conjunto de datos extraído directamente desde una fuente JSON pública, se realiza una exploración para conocer su estructura, identificar problemas de calidad y preparar los datos para futuros análisis más complejos, como segmentación de clientes o modelos predictivos de abandono (*churn*).

## 🧠 Objetivo del proyecto

El propósito principal es llevar a cabo una **evaluación de la calidad de los datos**, a través de procesos de limpieza, detección de errores comunes (como duplicados o valores faltantes) y comprensión de la distribución de los datos por columna. Este tipo de análisis es esencial como paso previo en cualquier proyecto de ciencia de datos o aprendizaje automático.

## 📂 Contenido del proyecto

El proyecto se encuentra dentro de un archivo Jupyter Notebook:  
📄 `Telecom_P1.ipynb`

Este archivo contiene todas las celdas necesarias, organizadas en secciones, que incluyen:

1. **Importación de librerías** (`requests`, `pandas`)
2. **Obtención de datos desde un enlace JSON**
3. **Conversión a DataFrame plano con `pd.json_normalize()`**
4. **Visualización general del dataset**
5. **Conteo de valores únicos por columna**
6. **Revisión de duplicados**
7. **Análisis de valores nulos y campos vacíos**

## ⚙️ Tecnologías y herramientas utilizadas

- 🐍 **Python 3.** Lenguaje principal del análisis  
- 📦 **Pandas.** Librería para análisis y manipulación de datos  
- 🌐 **Requests.** Para descargar datos desde una URL externa  
- 🧪 **Jupyter Notebook.** Entorno interactivo para desarrollo paso a paso

## 💡 ¿Qué se aprende con este proyecto?

- Cómo conectar tu código a fuentes de datos externas (como archivos JSON en línea).
- Técnicas de transformación de datos anidados a estructuras planas y analizables.
- Métodos para identificar problemas comunes en datasets reales:
  - Datos duplicados
  - Valores nulos
  - Campos vacíos o mal formateados
- Interpretación inicial de la calidad del dataset antes de aplicar técnicas estadísticas o de machine learning.

## ▶️ ¿Cómo usar este repositorio?

- Clona el repositorio

## Autor

Desarrollado por [Alan Guillen](https://github.com/MickGuillen)

