Contributing to Physrisk
==============================

## Getting started

To get set up and run tests, clone repo and then run:
```
pip install -r requirements.txt
cd src
pytest
```

Using a Python virtual environment is recommended. For example if using VS Code:
```
python3 -m venv .venv
code .
```
Then in VS Code:
```
source .venv/bin/activate
```
## Project Organization
------------
Follows conventions of Cookiecutter Data Science

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── Pipfile            <- Pipfile stating package configuration as used by Pipenv.
    ├── Pipfile.lock       <- Pipfile.lock stating a pinned down software stack with as used by Pipenv.
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
    ├── requirements.txt   <- The requirements file stating direct dependencies if a library
    │                         is developed.
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
    ├── .thoth.yaml        <- Thoth's configuration file
    ├── .aicoe-ci.yaml     <- AICoE CI configuration file (https://github.com/AICoE/aicoe-ci)
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------