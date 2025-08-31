# UV-Prolif

## Descripción
UV-Prolif es un proyecto de análisis molecular que utiliza ProLIF (Protein-Ligand Interaction Fingerprints) para analizar y visualizar interacciones entre proteínas y ligandos en simulaciones de dinámica molecular.

## Requisitos
- Python >= 3.13
- MDAnalysis >= 2.9.0
- MDTraj >= 1.11.0
- ProLIF
- RDKit >= 2025.3.5
- Seaborn >= 0.13.2
- py3Dmol >= 2.5.2
- Jupyter y extensiones relacionadas

## Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/RenatoJVA/UV-Prolif.git
cd UV-Prolif
```

2. Crear y activar el entorno virtual usando uv:
```bash
uv venv
# En Windows:
.venv\Scripts\activate
# En Unix/MacOS:
source .venv/bin/activate
```

3. Instalar dependencias:
```bash
uv pip install
```

## Uso

El proyecto incluye un notebook Jupyter (`Prolif.ipynb`) que contiene:

1. Carga de sistemas moleculares
2. Análisis de interacciones proteína-ligando
3. Generación de fingerprints de interacción
4. Visualización de resultados
   - Redes de interacción
   - Mapas de calor de similitud
   - Visualizaciones 3D

Para iniciar el análisis:

```bash
uv run --with jupyter jupyter lab
```

## Características

- Análisis de trayectorias de dinámica molecular
- Detección automática de interacciones proteína-ligando
- Generación de fingerprints de interacción
- Visualización interactiva de resultados
- Cálculo de similitud entre frames
- Exportación de resultados para análisis posteriores

## Licencia

Este proyecto está bajo la Licencia MIT.

## Autor

Renato J. Vargas Alvarado
