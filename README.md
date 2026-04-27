# Musical Profile Clustering

Este proyecto analiza y agrupa perfiles musicales usando técnicas de aprendizaje no supervisado.

## Estructura de carpetas

- `data/`
  - Almacena los datos crudos y procesados utilizados en el análisis.
  - `data/raw/`: datos originales sin limpiar.
  - `data/processed/`: datos transformados, muestreados y escalados para el modelado.
  - Nota: los conjuntos de datos completos no están incluidos aquí porque superan los 100 MB y no se pueden subir a GitHub.
    Para reproducir el proyecto, puede obtener los datos desde:
    `https://www.kaggle.com/datasets/asaniczka/top-spotify-songs-in-73-countries-daily-updated/data`

- `docs/`
  - Contiene la documentación del proyecto y el informe en formato IEEE.
  - `docs/main.tex`: archivo principal de LaTeX del informe.
  - `docs/references.bib`: bibliografía del informe.
  - `docs/figures/`: figuras y gráficos usados en el documento.
  - `docs/sections/`: secciones del informe organizadas por temas.

- `notebooks/`
  - Notebooks de Jupyter que muestran los experimentos, comparativas y análisis de los algoritmos de clustering.
  - `Agglomerative_Clustering.ipynb`: análisis usando clustering aglomerativo.
  - `DBSCAN.ipynb`: análisis usando DBSCAN.
  - `K-Means.ipynb`: análisis usando K-Means.

- `src/`
  - Scripts de Python de apoyo para limpieza, preparación de datos y utilidades usadas por el proyecto.
  - `src/main.py`: script principal de apoyo para ejecutar procesamiento o análisis.

- `requirements.txt`
  - Lista de dependencias necesarias para reproducir el proyecto.

## Notas rápidas

1. Usa `requirements.txt` para instalar las librerías necesarias.
2. Revisa `notebooks/` para ver cómo se aplican las técnicas de clustering y las comparativas entre algoritmos.
3. El flujo típico es: datos en `data/raw/` → transformación en `data/processed/` → experimentos en `notebooks/`.
4. `src/` son scripts de apoyo; pueden servir para limpieza de datasets y otras utilidades del proyecto.
