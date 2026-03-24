# {{cookiecutter.project_name}}

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

{{cookiecutter.description}}

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; and Notes, figures, or method description for preprints/papers.
│
├── scripts            <- Single-task runners
│
├── experiments        <- Jupyter notebooks for exploration, analysis, simulations, or ablations. Naming convention is a
│                          number (for ordering), the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
├── pipelines          <- Orchestrate multi-step workflows: e.g., preprocess → train → benchmark → evaluate. 
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         {{ cookiecutter.module_name }} and configuration for tools like black
├── results            <- Generated outputs: model checkpoints, embeddings, metrics tables, figures.
│
├── configs            <- YAML/JSON files for hyperparameters, datasets, or experiment setups.
│
├── tests
│
└── {{ cookiecutter.module_name }}   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes {{ cookiecutter.module_name }} a Python module
    │    
    ├── datasets.py             <- Scripts to download or generate data
    │
    ├── models.py               <- Model definitions/classes 
    │                           
    ├── training.py             <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

