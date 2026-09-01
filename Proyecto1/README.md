# 🛒 Análisis de Comportamiento de Compra — Instacart

## 📌 Descripción del proyecto

Este proyecto analiza datos históricos de pedidos de Instacart con el objetivo de comprender el comportamiento de compra de los clientes.

A partir de diferentes conjuntos de datos relacionados con pedidos, productos y usuarios, realicé un proceso completo de limpieza, transformación y análisis exploratorio para identificar patrones de compra, frecuencia de pedidos y comportamiento de recompra.

El proyecto forma parte de mi portafolio de análisis de datos y busca demostrar mi capacidad para transformar datos sin procesar en información útil y comprensible.

---

## 🎯 Objetivo

Analizar el comportamiento de los clientes para responder preguntas como:

- ¿A qué horas y días realizan más pedidos los usuarios?
- ¿Cuántos pedidos realiza normalmente cada cliente?
- ¿Cuántos productos contiene un pedido?
- ¿Qué productos son los más comprados?
- ¿Qué productos presentan una mayor frecuencia de recompra?
- ¿Qué productos suelen agregarse primero al carrito?
- ¿Qué proporción de productos comprados corresponde a artículos previamente adquiridos?

---

## 🗂️ Datos utilizados

El análisis utiliza diferentes conjuntos de datos relacionados entre sí:

- Pedidos realizados.
- Productos disponibles.
- Departamentos de productos.
- Pasillos o categorías.
- Productos incluidos en cada pedido.

Para realizar el análisis fue necesario relacionar información procedente de diferentes tablas.

---

## 🧹 Preparación y limpieza de datos

Antes del análisis realicé distintas tareas de preparación:

- Revisión de tipos de datos.
- Identificación de valores ausentes.
- Detección y tratamiento de registros duplicados.
- Validación de rangos y valores.
- Exploración de valores únicos.
- Agrupación de información por pedidos, usuarios y productos.
- Unión de diferentes DataFrames mediante `merge`.

---

## 🔎 Análisis exploratorio

Durante el proyecto analicé diferentes aspectos del comportamiento de los clientes.

### 📦 Comportamiento de los pedidos

- Distribución de pedidos por usuario.
- Cantidad de productos incluidos en cada pedido.
- Horarios con mayor actividad.
- Frecuencia de compra de los clientes.

### 🔄 Recompra de productos

Analicé qué productos eran adquiridos nuevamente por los clientes y calculé la proporción de recompra de cada producto.

Esto permitió comparar productos no solo por su volumen total de ventas, sino también por la frecuencia con la que los clientes decidían volver a comprarlos.

### 🛒 Productos añadidos primero al carrito

También analicé qué productos aparecían con mayor frecuencia como el primer artículo agregado al carrito.

Este análisis permite identificar productos que pueden tener una importancia especial dentro del proceso de compra del cliente.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

---

## 💻 Técnicas utilizadas

Durante el proyecto trabajé con herramientas y operaciones como:

- `groupby()`
- `merge()`
- `value_counts()`
- `duplicated()`
- `nunique()`
- `describe()`
- `sort_values()`
- Filtros condicionales
- Cálculo de proporciones
- Estadística descriptiva
- Histogramas
- Gráficos de barras
- Análisis de distribuciones

---

## 📊 Habilidades demostradas

Este proyecto demuestra experiencia práctica en:

- Limpieza y preparación de datos.
- Manipulación de múltiples DataFrames.
- Análisis exploratorio de datos (EDA).
- Estadística descriptiva.
- Identificación de patrones de comportamiento.
- Visualización de información.
- Interpretación de resultados.
- Comunicación de hallazgos mediante código, tablas y gráficas.

---

## 💡 Aprendizajes del proyecto

Este análisis me permitió trabajar con un conjunto de datos compuesto por múltiples tablas y comprender la importancia de validar la información antes de realizar cualquier análisis.

También reforcé el uso de agrupaciones, uniones y métricas relativas para estudiar el comportamiento de los clientes desde diferentes perspectivas, en lugar de limitarme únicamente a conteos generales.

---

## 🚀 Próximas mejoras

Como continuación del proyecto, sería posible incorporar:

- Segmentación de clientes según sus hábitos de compra.
- Análisis de categorías y departamentos.
- Análisis de productos comprados conjuntamente.
- Modelos para estimar la probabilidad de recompra.
- Visualizaciones adicionales orientadas a presentación ejecutiva.

---

## 👤 Autor

**Emmanuel**

Proyecto desarrollado como parte de mi formación y portafolio en Análisis y Ciencia de Datos.
