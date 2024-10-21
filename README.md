# Trabajo Práctico N°1 - Minería de Datos

Este repositorio contiene el Trabajo Práctico N°1 para la materia de Minería de Datos (2024), cuyo objetivo es aplicar las técnicas aprendidas a un problema real asociado a los cultivos, utilizando el dataset de **dxCropRecommendation.csv**.

## Objetivo

El propósito principal de este trabajo es explorar técnicas de reducción de dimensionalidad y análisis de clusters para entender los datos, así como obtener conclusiones útiles en el contexto de la agricultura.

## Estructura del Proyecto

El proyecto está dividido en varias etapas que incluyen las siguientes actividades:

1. **Análisis de los atributos del dataset**: Exploración de distribuciones, outliers, y tipos de datos. Selección de un método de estandarización adecuado.
2. **Reducción de dimensionalidad con PCA**: Realización de un análisis de componentes principales, determinación del número óptimo de componentes y visualización en 2D/3D.
3. **Aplicación de Isomap**: Variación del número de vecinos y componentes, y visualización de los resultados en 2D.
4. **Aplicación de t-SNE**: Variación de parámetros como iteraciones y perplejidad, con visualización en 2D.
5. **Subconjunto de frutas**: Aplicación de PCA sobre un subconjunto que incluye frutas como Granada, Banana, Mango, entre otras, con visualización en 2D.
6. **Clustering con K-means**: Análisis variando el número de clusters y determinación del número óptimo utilizando el método GAP. Visualización en 3D.
7. **Clustering jerárquico**: Determinación del número óptimo de clusters utilizando el método de Silhouette y GAP.

## Archivos

- **TP_MDD_Avecilla_Calcia.ipynb**: Contiene el desarrollo completo del trabajo práctico.
- **TP1.pdf**: Enunciado oficial del trabajo práctico.

## Requisitos

- Python 3.x
- Librerías necesarias (Pandas, Scikit-learn, Matplotlib, etc.)

Para instalar las dependencias, ejecutar:

```bash
pip install -r requirements.txt
```

## Uso

Para ejecutar el notebook:

1. Clona el repositorio: 
    ```bash
    git clone https://github.com/FrancoCalcia/Mineria-de-Datos-TP1.git
    ```
2. Accede al directorio del proyecto:
    ```bash
    cd tu_repositorio
    ```
3. Abre el archivo `.ipynb`:
    ```bash
    notebook TP_MDD_Avecilla_Calcia.ipynb
    ```

## Conclusiones

Al final del trabajo se presentan conclusiones basadas en los análisis realizados y las técnicas aplicadas, proporcionando insights sobre el comportamiento de los datos agrícolas y la efectividad de las técnicas utilizadas.
