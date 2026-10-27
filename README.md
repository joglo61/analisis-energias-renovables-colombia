# Análisis de energías renovables no convencionales en Colombia

Proyecto final del bootcamp de Análisis de Datos Nivel Básico (MinTIC Talento Tech, 159 h).

## Objetivo

Analizar los proyectos de energías renovables no convencionales (solar y eólica) en Colombia: capacidad instalada, inversión, empleos estimados y emisiones de CO₂, por proyecto y por departamento.

## Datos

- `datosplanb.csv`: más de 150 proyectos. Fuente: datos abiertos del Ministerio de Minas y Energía (datos.gov.co).
- `co.json`: geometrías de los departamentos de Colombia, usadas para los mapas.

## Contenido

- `analisis_energias_renovables.ipynb`: limpieza, análisis y visualizaciones.

## Herramientas

Python, pandas, NumPy, matplotlib, seaborn, plotly, geopandas, scikit-learn (K-Means) y yellowbrick.

## Resultados principales

- Cerca del 92 % de los proyectos son solares y el 8 % eólicos.
- La Guajira concentra la mayor inversión estimada.
- La correlación entre empleos estimados y emisiones de CO₂ es de 0,76.
- K-Means agrupa los proyectos en 3 segmentos según inversión, empleos y emisiones.

## Cómo ejecutarlo

1. Abre el cuaderno en Google Colab.
2. Sube `datosplanb.csv` y `co.json` a la carpeta `/content`.
3. Ejecuta las celdas en orden.
