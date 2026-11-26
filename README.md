# Actividad 4

Grupo G

Integrantes: Alejandra Suesca, María Camila Hoyos, Yanin Mejía

Fuente de datos: Our World in Data, https://ourworldindata.org/co2-emissions

## Objetivo

Analizar la evolución de las emisiones de CO₂, compararlas entre países y construir un modelo de regresión lineal para interpretar su relación con variables como el PIB y la población.

## Datos

- Dataset: `owid-co2-data.csv`
- Registros: 56.269 filas, 79 columnas
- Variables principales:
  - `co2`: emisión total de CO₂
  - `co2_per_capita`: emisión por persona
  - `population`: población
  - `gdp`: PIB

## Procedimiento

1. Cargar los datos
2. Filtrar columnas principales
3. Eliminar agregados y regiones
4. Truncar a partir de 1950
5. Quedarnos solo con países con datos completos en las variables de interés

## Resultados principales

- Se limpian y filtran los datos para trabajar con países reales, sin agregados ni nulos problemáticos.
- Se hace una gráfica de la evolución de las emisiones de CO₂ en Colombia para ilustrar el análisis.
