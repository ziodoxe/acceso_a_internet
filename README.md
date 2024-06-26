Análisis de Acceso a Internet en la Provincia de Tierra del Fuego e IAS
==============================

## Descripción

Este proyecto se centra en el análisis y predicción al acceso a internet utilizando diversas técnicas de ciencia de datos y aprendizaje automático. El objetivo es identificar patrones en los datos sobre el uso de otras tecnologías de la información y comunicación y desarrollar modelos predictivos para clasificar al individuo su cercania con la tecnologia, etiquetandolo como MEDIO, BAJO, ALTO. Teniendo en cuanta las variables de:

1) IP_III_04 (En los últimos meses, ¿utilizó internet?)
2) IP_III_05 (En los últimos tres meses, excluyendo el uso de internet, ¿utilizó computadora?)
3) IP_III_06 (En los últimos tres meses, ¿utilizó un teléfono móvil (celular)?)

Podremos clasificarlos en:
Si es verdadero los items 1, 2 y 3 como ALTO.
Si es verdadero los items 1 y 2 como MEDIO.
Si es verdadero el items 1 como BAJO.

Cualquier otra combinacion no se tomara en cuanta.


Los detalles se encuentran en el archivo 'DescripcionDeDatos.md' que se encuentra en la carpeta 'docs'.

link: https://sitioanterior.indec.gob.ar/bases-de-datos.asp

## Estructura del Proyecto

La estructura del proyecto sigue la plantilla Cookiecutter Data Science y es la siguiente:

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
