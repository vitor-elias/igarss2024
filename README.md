# Graph-based Fault Detection and Localization in InSAR Data

## Overview

This repository contains the code and experiments conducted for the paper titled "Graph-based Fault Detection and Localization in InSAR Data."


## Google Colab
Can be easily run on Google Colab  
Requires installation of some of the packages listed below. Overwrite scipy==1.8.1

## Requirements

To run the experiments in this repository, ensure you have Python installed (version >=3.10,<3.11).  
Runs on Mac M1.  
Dependencies are managed using Poetry.  
Some torch-geometric dependencies can be installed via pip.  

```bash
poetry install
```

This will install all the required dependencies, including but not limited to:

- python = ">=3.10,<3.11"
- numpy = "<1.23"
- jupyter = "^1.0.0"
- pandas = "^2.1.4"
- optuna = "^3.5.0"
- matplotlib = "^3.8.2"
- plotly = "^5.18.0"
- scikit-learn = "^1.3.2"
- scipy = "1.8.1"
- pygsp = "^0.5.1"
- pyprojroot = "^0.3.0"
- jupyterlab = "^4.0.9"
- ipykernel = "^6.27.1"
- tensorflow = "2.13.0"
- numba = "0.57.1"
- torch = "2.0.1"
- torchvision = "0.15.2"
- torch-geometric = "2.3.1"
- torchviz = "0.0.2"


```bash
pip install torch-sparse==0.6.17 torch-scatter==2.1.1 torchmetrics==1.0.3
```

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/vitor-elias/igarss2024.git
    cd igarss2024
    ```

2. Install dependencies:

    ```bash
    poetry install
    ```

## Folder and files

- `notebooks/`: Jupyter notebooks for different experiments.
    - `synthetic_experiments.ipynb`: experiments using synthetic graphs and data
    - `utils.ipynb`: definitions for useful supporting functions

