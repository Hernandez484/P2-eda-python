# P2 · Exploratory Data Analysis — Northwind Sales

Análisis exploratorio de datos de ventas usando Python sobre el dataset Northwind. Continuación del análisis financiero realizado en P1 con SQL.

## Objetivo

Limpiar, explorar y visualizar los datos de ventas Northwind para identificar patrones de ingresos, tendencias temporales y productos clave.

## Herramientas

- Python 3
- Pandas 2.3.3
- Matplotlib 3.10.6
- Seaborn 0.13.2
- VS Code + Jupyter

## Estructura del proyecto

P2-eda-python/
├── data/
│   └── northwind_sales.csv
├── notebooks/
│   └── eda_northwind.ipynb
└── README.md

## Hallazgos principales

- **Beverages** domina con ~$38,000 en ingresos — más del 55% del total.
- **Northwind Traders Coffee** es el producto #1 con ~$30,000.
- **Marzo 2006** registra un pico de ~$32,000 impulsado por órdenes masivas de Coffee.
- Se detectaron **4 outliers en revenue** (>$2,595), todos ventas reales extraordinarias.
- Alto riesgo de concentración: un producto en una categoría impulsa los resultados globales.

## Visualizaciones

1. Ingresos totales por categoría (bar chart).
2. Tendencia mensual de ingresos (line chart).
3. Distribución de precios por categoría (boxplot).
4. Top 10 productos por ingreso (bar chart).
5. Distribución de revenue con outliers (boxplot).

## Relación con P1

Este proyecto visualiza los hallazgos del análisis SQL del P1.
Repositorio P1: [P1 · SQL Financial Analysis](https://github.com/Hernandez484/P1-sql-financial-analysis)