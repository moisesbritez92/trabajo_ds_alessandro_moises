# Trabajo Práctico de Data Science

Proyecto colaborativo de Ciencia de Datos desarrollado por [@moisesbritez92](https://github.com/moisesbritez92) y [@aflammia](https://github.com/aflammia).

## Descripción

Este repositorio documenta un análisis del rendimiento académico de estudiantes portugueses a partir del dataset **Student Performance** (UCI). El trabajo integra limpieza de datos, análisis exploratorio, pruebas estadísticas y modelos predictivos para explicar y estimar la calificación final (**G3**).

## Objetivo general

Identificar qué factores demográficos, familiares y académicos influyen en el rendimiento estudiantil y evaluar la capacidad predictiva de distintos enfoques estadísticos y de machine learning.

## Alcance del análisis

- Análisis exploratorio de datos (EDA).
- Pruebas de hipótesis (por ejemplo, diferencias por sexo y nivel educativo familiar).
- Reducción de dimensionalidad (PCA).
- Modelos de regresión para predecir la nota final (G3).
- Modelos de clasificación para predecir aprobación/reprobación.

## Dataset

Se utilizan los archivos originales del dataset de rendimiento estudiantil:

- `dataset/student-mat.csv`
- `dataset/student-por.csv`
- `dataset/student.txt` (documentación de variables)
- `variable_table.txt` (tabla descriptiva de variables)

## Stack utilizado

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn, scipy
- Jupyter Notebook

Dependencias completas en `requirements.txt`.

## Estructura actual del repositorio

```bash
.
├── dataset/
│   ├── student-mat.csv
│   ├── student-merge.R
│   ├── student-por.csv
│   └── student.txt
├── Informe/
│   ├── informe.tex
│   └── informe.aux
├── heta_graf.ipynb
├── project_student_dataset.ipynb
├── trabajo.ipynb
├── variable_table.txt
├── requirements.txt
└── README.md
```

## Cómo ejecutar el proyecto

1. Clonar el repositorio.
2. Crear y activar un entorno virtual.
3. Instalar dependencias.
4. Abrir y ejecutar los notebooks.

### Ejemplo (Windows PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
jupyter notebook
```

## Orden sugerido de lectura/ejecución

1. `project_student_dataset.ipynb` (flujo principal del análisis).
2. `trabajo.ipynb` (experimentos y desarrollo complementario).
3. `heta_graf.ipynb` (visualizaciones específicas).
4. `Informe/informe.tex` (documentación final del trabajo).

## Integrantes

- **Moises Britez** — [@moisesbritez92](https://github.com/moisesbritez92)
- **Alessandro Flammia** — [@aflammia](https://github.com/aflammia)

> MADI
