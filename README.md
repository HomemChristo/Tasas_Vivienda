# Tasas de Credito en Vivienda en Colombia

By: homemchristo.

Version: 0.1.0

The objective of this proyect is to compile the results obtained from the analysis of the data set of the interest rates for housing offered in Colombia in the year 2023, in order to be able to find a trend and at the same time answer some of the most common questions. frequently encountered by the public who wants to obtain a mortgage loan, making use of the tools provided by data science and the different machine learning algorithms.

## Prerequisites

- [Anaconda](https://www.anaconda.com/download/) >=4.x

## Create environment

```bash
conda env create -f environment.yml
activate Tasas_Vivienda
```

## Clone the proyect:

```sh
git clone
python3 -m Tasas_vivienda env
source env/bin/activate
pip3 install -r requirements.txt
```


## Project organization

    Tasas_Vivienda
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering)
        │                         
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    
        │
        ├── requirements.txt   <- The requirements file for reproducing the analysis environment.
        |
        └── README.md          <- The top-level README for developers using this project.

---