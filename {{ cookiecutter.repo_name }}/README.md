{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   ├── features       <- Features may be stored here
│   ├── inference      <- Inference stages may be stored here
│   └── raw            <- The original, immutable data dump.
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
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── .pre-commit-config.yaml <- Stores pre-commit settings
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── __init__.py
│
└── {{cookiecutter.repo_name}}   <- Source code for use in this project.
    ├── __init__.py    <- Makes {{cookiecutter.repo_name}} a Python module
    │    
    ├── settings.py <- illustrates how to use .env file
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── featurize.py
    │
    └── models         <- Scripts to train models and then use trained models to make
        │                 predictions
        └── train.py
```
