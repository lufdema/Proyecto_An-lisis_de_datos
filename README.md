# Análisis Predictivo y Estadístico de Sneaker Reselling en StockX

Este proyecto realiza un análisis exhaustivo del mercado de reventa de sneakers utilizando datos de la plataforma **StockX**. Combina técnicas estadísticas, exploración de datos y modelado predictivo para identificar patrones de precios, factores que influyen en la rentabilidad, y oportunidades para maximizar ganancias en este mercado.

## Contenido del Proyecto

### 1. Introducción
- Contexto del mercado de reventa de sneakers.
- Objetivo: Comparar precios de lanzamiento con precios de reventa y predecir tendencias de valor en el tiempo.

### 2. Carga y Descripción de Datos
- **Carga de Datos:** Uso de datos obtenidos de **StockX** y otros recursos, incluyendo mapas para análisis geográfico.
- **Descripción de los Datos:** Exploración inicial de las variables relevantes como precios de retail, precios de reventa, tallas, y fechas de lanzamiento.

### 3. Análisis Exploratorio y Estadístico
- **Pérdidas para los Vendedores:** Identificación de modelos menos rentables y análisis de costos asociados con transacciones.
- **Impacto de la Talla:** Análisis de varianza para determinar si las tallas influyen en los precios de reventa.
- **Factores Predictivos:** Regresión multivariable para predecir precios de reventa en función de talla y días desde el lanzamiento.

### 4. Modelado Predictivo
- **Regresión Lineal:** Creación de un modelo para predecir precios futuros basado en datos históricos.
- **Validación:** Comparación del modelo con precios reales, obteniendo un error porcentual bajo (~7%).

### 5. Análisis de Outliers
- Identificación de los sneakers más valiosos basándose en precios atípicos.
- Uso del rango intercuartílico (IQR) para encontrar modelos destacados y visualización interactiva.

### 6. Análisis Geográfico
- **Ventas por Estado:** Visualización de las ventas totales en Estados Unidos a nivel estatal mediante mapas coropléticos.
- Identificación de tendencias de consumo en estados clave como California, Florida y Nueva York.

## Uso del Código
1. **Requisitos Previos:** Instalar las librerías necesarias (pandas, geopandas, statsmodels, seaborn, plotly, etc.).
2. **Ejecución:** Cargar el archivo Jupyter Notebook en un entorno compatible y ejecutar las celdas secuencialmente.

## Resultados
- Identificación de factores clave que afectan los precios de reventa, incluyendo talla, días desde el lanzamiento, y marcas específicas.
- Creación de modelos predictivos con alta precisión para evaluar el valor de sneakers en el mercado de reventa.
- Visualización interactiva de datos, facilitando el análisis para tomadores de decisiones y revendedores.
- Conclusiones sobre las marcas más rentables (e.g., Nike frente a Adidas) y las regiones donde se concentra el mayor volumen de ventas (California lidera).

## Referencias
1. **Russell, C.** (2021, December 10). Adidas or Nike? Which Retail Giant Is Winning the Sneakers War? *Forbes*. [Enlace](https://www.forbes.com/sites/callyrussell/2019/08/22/adidas-or-nike-which-retail-giant-is-winning-the-sneakers-war/?sh=47bdd25512b7)
2. **Miller, C.** (2021, October 20). What Is the Average Shoe Size for Men? The Answer Might Surprise You. *Footwear News*. [Enlace](https://footwearnews.com/feature/average-shoe-size-men-1202752232/)
3. **US Department of Commerce, NOAA.** (2023, January 17). U.S. States and Territories. *National Weather Service*. [Enlace](https://www.weather.gov/gis/USStates)
4. **Leach, W. B. A.**, & **Writer/Editor/Consultant, A. L. F.** (2015, July 6). Here's How Every U.S. State Ranks in Sneaker Reselling. *Highsnobiety*. [Enlace](https://www.highsnobiety.com/p/best-sneaker-resell-states/)
5. Observaciones propias del mercado y análisis de datos de StockX.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Puedes consultar el archivo `LICENSE` para más detalles.

---
