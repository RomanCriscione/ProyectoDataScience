# Entrega Final — Roman Criscione

## Descripción
Notebook del proyecto final del curso **Data Science 1** (Coderhouse).  
Incluye selección de características (*feature selection*), modelo de regresión lineal y evaluación con métricas básicas.

## Contenido
- `ProyectoParteIII_Criscione.ipynb`: notebook con todo el desarrollo.
- `cryptocurrency.csv`: dataset con snapshot de criptomonedas.

## Tecnologías utilizadas
- Python 3
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## Cómo ejecutar
1. Clonar este repositorio.
2. Abrir el notebook en Jupyter o Google Colab.
3. Asegurarse de que `cryptocurrency.csv` esté en la misma carpeta.
4. Ejecutar todas las celdas de arriba a abajo.

## Resultados
El modelo logra una ligera mejora frente al baseline, mostrando cierta capacidad predictiva.  
Las variables con mayor peso son `chg_7d_pct`, `total_vol_pct` y `vol_24h_num`.

## Autor
**Roman Criscione**
