Análisis exploratorio de la producción de petróleo en Colombia entre el año 2017 al 2021.
==============================

Se realiza un análisis exploratorio de los datos de 5 datasets diferentes que contienen información 
sobre la producción mensual de los principales pozos petroleros de Colombia entre los años 2017 al 2021.
Buscando responder como afecto la pandemia del covid-19 la producción general de petróleo.

Link proyecto Deepnote: https://deepnote.com/@julianbarr368/Produccion-petroleo-Colombia-2017-2021-0fd3e98d-bed4-4d63-b92c-a6f754667634


Carpeta notebooks:
==============================

1. 1.0_JB_transform_load.ipynb --> Se realiza el proceso de ETL de los datos.

2. 2.0_JB_data_exploration.ipynb --> Se realiza un análisis exploratorio de los datos.

3. 3.0_JB_analysis and conclusions.ipynb --> Se explican las conclusiones extraídas de los datos.

4. 4.0_JB_project integration --> Se reune todas los notebooks para mostar como proyecto.


Link's Dataset: 
==============================

Dataset 2017: https://www.datos.gov.co/Minas-y-Energ-a/Producci-n-Fiscalizada-de-Petr-leo-2017/py6n-xwnk

Dataset 2018: https://www.datos.gov.co/Minas-y-Energ-a/Producci-n-Fiscalizada-de-Petr-leo-2018/wpjb-8um2

Dataset 2019: https://www.datos.gov.co/Minas-y-Energ-a/Producci-n-Fiscalizada-de-Petr-leo-2019/vcuy-z8kj

Dataset 2020: https://www.datos.gov.co/Minas-y-Energ-a/Producci-n-y-Regal-as-por-Campo-2020/w79x-qwdk

Dataset 2021: https://www.datos.gov.co/Minas-y-Energ-a/Producci-n-Fiscalizada-de-Petr-leo-2021/i5aj-8t8t


link's information sources:
==============================

1. https://www.banrepcultural.org/biblioteca-virtual/credencial-historia/numero-151/la-industria-petrolera-en-colombia

2. https://datosmacro.expansion.com/energia-y-medio-ambiente/petroleo/produccion/colombia

3. https://www.valoraanalitik.com/2022/08/04/colombia-produccion-petroleo-junio-mas-alta-desde-2020/#:~:text=Lea%20m%C3%A1s%20en%20noticias%20de,cuando%20fue%20de%20760.020%20bopd.


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- Project information.
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
