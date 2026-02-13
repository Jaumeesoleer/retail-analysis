# 🛒 Análisis de Ventas Retail – Proyecto de Insights de Negocio

## 📌 Descripción General del Proyecto

Este proyecto analiza un dataset transaccional de retail para extraer insights de negocio relacionados con los ingresos, el comportamiento del cliente y los patrones de estacionalidad.

El objetivo es simular el flujo de trabajo real de un Data Analyst:  
limpieza de datos, análisis exploratorio (EDA), feature engineering y conclusiones orientadas al negocio.

---

## 🎯 Objetivos de Negocio

- Identificar las categorías con mejor desempeño
- Detectar patrones de estacionalidad
- Analizar la demografía de clientes
- Evaluar la consistencia de precios
- Extraer recomendaciones accionables para el negocio

---

## 📂 Descripción del Dataset

- ~1000 transacciones
- 998 clientes únicos (sin recurrencia de compra)
- Variables incluidas:
  - Fecha
  - Categoría
  - Cantidad
  - Precio por Unidad
  - Importe Total
  - ID de Cliente
  - Género
  - Edad

⚠️ **Nota:** Cada cliente aparece solo una vez, lo que impide realizar análisis de recurrencia o retención.

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🔍 Metodología

1. Limpieza y validación de datos
2. Verificación de consistencia de ingresos
3. Feature engineering (Mes, Día de la semana)
4. Análisis de ingresos por categoría
5. Segmentación demográfica de clientes
6. Análisis temporal (patrones mensuales y por día de la semana)

---

## 📊 Insights Clave

### 🥇 Desempeño por Categoría

- **Electrónica** lidera los ingresos totales (~$156k)
- **Ropa** le sigue de cerca (~$155k)
- **Belleza** tiene el ticket promedio más alto (~$464), lo que sugiere alto valor por transacción pero menor volumen

---

### 📈 Estacionalidad

- **Mayo** es el mes con mayores ingresos (~$53k)
- **Septiembre** muestra una caída significativa (~$23k)
- La temporada navideña no supera a mayo, lo que indica una estacionalidad pico no tradicional

---

### 💰 Estructura de Precios

- Variación mínima en el precio promedio entre categorías
- Sugiere una estrategia de precios homogénea o posicionamiento de producto similar

---

### 👥 Comportamiento del Cliente

- Distribución de género equilibrada (~51% / 49%)
- Concentración de ingresos en los grupos de edad **18–35** y **42–64**
- Menor actividad de ingresos en el segmento **36–41**
- Sin recurrencia detectada (1 transacción por cliente)

---

## 🚀 Próximos Pasos Potenciales

- Añadir granularidad a nivel de producto
- Incorporar datos geográficos
- Realizar análisis de cohortes con compras recurrentes
- Desarrollar un dashboard en Power BI para visualización ejecutiva

## 📬 Contacto

¿Te ha gustado este análisis? ¡Conectemos!

- Autor: Jaume Soler

- LinkedIn: [Jaume Soler](https://www.linkedin.com/in/jaume-soler-sanchez-432675234?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
