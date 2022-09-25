# ¿En qué tipo de obras invirtió más el Ministerio de Obras Pública (M.O.P.) de Chile entre los años 2010-2021?

Análisis de datos de las inversiones M.O.P entre loas años 2010-2021. En el [notebook de análisis](https://github.com/lextomato/data_inveriones_mop_2010_2021/blob/master/notebooks/2_exploracion.ipynb) se responden las siguientes preguntas:
- ¿En qué tipo de obras invierte más M.O.P.?
- ¿Cuáles son las 3 Regiones del país más beneficiadas en éstas inversiones?

Modelos para datos de las inversiones M.O.P entre loas años 2010-2021. En el [notebook de modelos](https://github.com/lextomato/data_inveriones_mop_2010_2021/blob/master/notebooks/4_modelacion_y_conclusiones.ipynb) se responden la siguiente pregunta:
- ¿Se podrá estimar las inversiones para los próximos años?

Estas son, entre otras, algunas de las conclusiones más importantes encontradas:
- Se ha demostrado que la mayor inverión que se hace anualmente son en Obras de Vialidad con un margen de diferencia muy notable respecto a los otros tipos de obra.
- La Región Metropolitana ha sido la más beneficiada, posteriormente en 2do lugar de ubican las obras no regionalizables y seguido en 3er lugar la región de Los Lagos, concluyendo así concentración de obras en la capital.
- Con la cantidad de características de este dataset no pueden hacer predicciones certeras, se recomienda agregar más características si existieran de otra fuente de datos para enriquecer dicho dataset y crear un modelo predictivo confiable.
- A través de un modelo no supervisado se encontró una brecha de anomalías en las inversiones, se recomienda evaluar más a fondo estos casos.

## Data
_Inversiones data_ extraída de:
- [Datos.gob](https://datos.gob.cl/en/dataset/31885/resource/a1bf892c-efb6-4a43-93c3-f9068e1b2381)

## Notebooks
Los notebooks siguen el siguiente patron::
1) Limpieza y carga
2) Exploración y Análisis
3) Enriquecimiento
4) Modelación y conclusiones

## Project organization

```
├── LICENSE.md
├── README.md                                              <- The top-level README for developers using this project.
├── serie_historica_inversiones_mop_2010-2021.xls          <- The original, immutable data dump.         
│
├── notebooks                                              <- Jupyter notebooks. Naming convention: number (for ordering),
│   ├── data
│   │   ├── clean_inversiones.csv                          <- The final canonical data sets for analysis.
│   │   └── enriched_inversiones.csv                       <- The final, canonical data sets for modeling.
│   │
│   ├── 1. process      
│   ├── 2. exploration and analysis
│   ├── 3. enrichment
│   └── 4. modeling
│
└── requirements.txt                                       <- The requirements file for reproducing the analysis environment.
```
