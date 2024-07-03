# 📊 Proyecto de Análisis de Desempeño de Campañas de Ventas A&B

## 🌟 Introducción
Este proyecto tiene como objetivo analizar el desempeño de las campañas de ventas para la empresa A&B utilizando Power BI. La herramienta Power BI permite visualizar datos de diferentes fuentes y crear informes interactivos que facilitan la toma de decisiones.

## 🗂️ Estructura del Proyecto
El proyecto está dividido en varias páginas, cada una de las cuales proporciona información clave sobre diferentes aspectos del desempeño de las campañas de ventas.

### 1. 🌐 Vista General
**Objetivo**: Proporcionar una visión general del desempeño de las campañas de ventas.

**Métricas Clave**:
- **💰 Monto total de ventas**: $1M
- **👥 Cantidad de clientes**: 2240
- **🌐 Visitas web mensuales**: 12K
- **📈 Campañas aceptadas**: 2668

**Gráficos**:
- **🏆 Productos Más Vendidos**: Muestra las categorías de productos con mayores ventas.
  - 🍷 **Wines**: $681K
  - 🍖 **Meat**: $374K
  - 🥇 **Gold**: $99K
- **🛒 Canales con mayor venta**: Comparación de las ventas a través de diferentes canales.
  - 🏬 **Store**: $12.970
  - 🌐 **Web**: $9.150
- **📊 Campañas con mayor respuesta**: Muestra las campañas con la mayor cantidad de respuestas.
  - **Campaign 4**: 668 respuestas
  - **Campaign 5**: 652 respuestas
  - **Campaign 3**: 652 respuestas
- **💎 Clientes con mayor valor**: Identifica a los clientes con mayor valor basado en su ID.
  - **ID cliente 9432**
  - **ID cliente 1503**
  - **ID cliente 1501**

### 2. 🛍️ Análisis de Productos
**Objetivo**: Analizar el desempeño de las diferentes categorías de productos.

**Gráficos**:
- **💸 Gasto promedio del cliente por categoría de productos**: Visualiza el gasto promedio en diferentes categorías de productos.
  - 🍷 **Wines**: $304
  - 🍖 **Meat**: $167
  - 🥇 **Gold**: $44
  - 🐟 **Fish**: $38
  - 🍬 **Sweet**: $27
  - 🍉 **Fruits**: $26
- **📊 Distribución de ventas por categoría de producto**: Muestra la participación porcentual de cada categoría de producto en las ventas totales.
- **📈 Porcentaje de ventas por canal**: Comparación de las ventas a través de diferentes canales.
- **🕑 Gasto en productos los últimos 2 Años**: Muestra el gasto total en productos durante los últimos dos años.

### 3. 👤 Análisis de Clientes
**Objetivo**: Proporcionar una visión detallada del perfil de los clientes y su comportamiento.

**Gráficos**:
- **🎓 Distribución de clientes por nivel educativo**: Visualiza el número de clientes según su nivel educativo.
- **💵 Gasto promedio por nivel educativo**: Muestra el gasto promedio de los clientes basado en su nivel educativo.
- **💍 Distribución de clientes por Estado Civil**: Visualiza la distribución de los clientes según su estado civil.
- **🤑 Distribución de ingresos por grupos de edad**: Muestra los ingresos totales por grupos de edad.
- **📚 Ingresos por Estado Civil y Nivel Educativo**: Comparación de ingresos según el estado civil y nivel educativo.
- **⏳ Distribución del tiempo de vida del cliente**: Muestra la distribución del tiempo de vida de los clientes en meses.

### 4. 📢 Análisis de Campañas
**Objetivo**: Analizar el desempeño de las campañas de marketing y su impacto en las ventas.

**Gráficos**:
- **📊 Distribución de respuestas por campaña**: Visualiza las respuestas positivas y negativas por campaña.
- **📈 Proporción de respuestas positivas y negativas**: Muestra la proporción de respuestas positivas y negativas.
- **👥 Distribución de clientes por rango de visitas**: Muestra el número de clientes según el rango de visitas web.
- **🌐 Visitas Web y Respuestas por Campaña**: Visualiza el número de visitas web y respuestas por campaña.
- **📉 Distribución de clientes según clientes y rangos de compra**: Muestra la distribución de clientes según los rangos de compra.
- **📊 Ratio de respuesta**: Muestra el porcentaje de respuestas obtenidas en comparación con el total de campañas.
- **😟 Ratio de quejas**: Muestra el porcentaje de quejas recibidas.
- **📈 Tasa de respuesta**: Muestra la tasa de respuesta de las campañas.

## 🔗 Relaciones entre Tablas
Las relaciones entre las diferentes tablas de datos son fundamentales para el análisis en Power BI. A continuación se muestra una descripción de las principales relaciones:
- **Customer Dim**: Relacionada con varias tablas de hechos, proporcionando detalles sobre los clientes.
- **Campaign Response Fact**: Contiene las respuestas a las campañas.
- **Purchases Product Fact**: Contiene detalles de las compras de productos.
- **Sales Channels Dim**: Proporciona información sobre los canales de venta.
- **Product Dim**: Contiene detalles de los productos vendidos.

## 📋 Conclusión
Este proyecto proporciona una herramienta poderosa para analizar el desempeño de las campañas de ventas de A&B. A través de visualizaciones interactivas y métricas clave, permite a los usuarios tomar decisiones informadas y mejorar las estrategias de marketing y ventas.
