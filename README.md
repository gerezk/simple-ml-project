# Forecasting Traffic Counts in Vienna, Austria

## Overview

The purpose of this project is to forecast traffic counts in the city of Vienna, Austria. Stadt Wien 
[reports](https://www.data.gv.at/katalog/datasets/4707e82a-154f-48b2-864c-89fffc6334e1) average, daily traffic counts 
for each month at certain locations. 

Research question:

> How does XGBoost perform in forecasting monthly average daily in Vienna, Austria using historical traffic data?

This project uses the dataset that was last updated on 20.11.2025.

## Tech Stack

- Python (3.12.12)
- Matploblib
- NumPy
- pandas
- scikit-learn
- XGBoost
- Jupyter Notebook

## Setup

If using Conda, install and activate the environment:

```
conda env create -f environment.yml
conda activate traffic-pred
```

Otherwise, install required packages:

```
pip install -r requirements.txt
```

## Licensing

The source code in this repository is licensed under the MIT License.
The data are © [Stadt Wien](https://www.data.gv.at/katalog/datasets/4707e82a-154f-48b2-864c-89fffc6334e1) and licensed under CC-BY-4.0.