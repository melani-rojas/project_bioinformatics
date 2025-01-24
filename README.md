# Proyecto de Análisis de Genes de Resistencia a Betalactámicos de genomas bacterianos

## Descripción del Proyecto
Este proyecto se enfoca en identificar y analizar los genes de resistencia a betalactámicos presentes en secuencias de bacterias patógenas, específicamente ***E. coli*** y ***Klebsiella pneumoniae***.

## Enlaces a Archivos Grandes

- [seq_project](https://drive.google.com/drive/folders/152cwM-1nBqGJ3dnvK1JY4YDOsJE8nL2C?usp=sharing) contiene las secuencias utlizadas y resultados de control de calidad, filtrado y anotación

## Scripts
-  `analyze_results.ipynb`: Script principal para análisis y visualización de datos.

## Datos
Los datos necesarios para ejecutar el script están en la carpeta `resultados.tsv`.

## Requisitos Previos
- Python 3.12.8
- Conda 24.11.1
## Entorno Conda
Para configurar el entorno conda, usa el archivo `environment.yml`.

## Instrucciones de uso
1. Clonar repositorio
`git clone https://github.com/melani-rojas/project_bioinformatics.git`

2. Configurar el Entorno
   `conda env create -f environment.yml`
3. Ejecutar script
   `jupyter notebook analyze_results.ipynb`
