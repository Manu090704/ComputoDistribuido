# Detección de lavado de dinero con PySpark y MLlib

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Manu090704/ComputoDistribuido/blob/main/BigData-A01711581-ManuelBajos.ipynb)

Proyecto de uso, procesamiento y visualización de grandes volúmenes de datos.

## Artefactos

- [Notebook de PySpark y MLlib](BigData-A01711581-ManuelBajos.ipynb)
- [Tablero en Tableau Public](https://public.tableau.com/app/profile/manuel.bajos.rivera/viz/EvidenciaLavadoDinero/DashboardLavadoDinero)
- [Captura del tablero](CapturaTablero.png)

## Dataset y alcance

El modelo se entrena con `LI-Small_Trans.csv` de IBM AML: 6,924,049 transacciones y 0.65 GB. `HI-Small_Trans.csv` se reserva como conjunto externo de predicción. El notebook documenta el significado de cada columna original, la adaptación realizada para MLlib y las decisiones de EDA.

## Ejecución

1. Abre el botón de Colab.
2. Ejecuta las celdas en orden.
3. El notebook descarga el dataset mediante KaggleHub, entrena con PySpark MLlib, genera gráficas intermedias con agregados Spark/Pandas/Matplotlib y exporta tablas agregadas para Tableau.
4. Si el notebook se mueve dentro del repositorio, actualiza la ruta del enlace de Colab.

El botón consulta `main`; por ello, cada actualización del notebook enviada a esa rama estará disponible al abrirlo en Colab.
