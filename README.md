# Graph-based Fault Detection and Localization in InSAR Data

## Overview

This repository contains the code and experiments conducted for the paper titled "Graph-based Fault Detection and Localization in InSAR Data." The paper explores novel techniques for detecting and localizing faults in Interferometric Synthetic Aperture Radar (InSAR) data using graph-based methods.

## Requirements

To run the experiments in this repository, ensure you have Python installed (version >=3.10,<3.11). Dependencies are managed using Poetry. 

```bash
poetry install
```

This will install all the required dependencies, including but not limited to:

numpy ^1.26.2
jupyter ^1.0.0
pandas ^2.1.4
torch ^2.1.1
torch-geometric ^2.4.0
optuna ^3.5.0
matplotlib ^3.8.2
plotly ^5.18.0
scikit-learn ^1.3.2
scipy ^1.11.4
pygsp ^0.5.1
pyprojroot ^0.3.0
jupyterlab ^4.0.9
torchvision ^0.16.1


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

3. Run the experiments:

    ```bash
    poetry run jupyter notebook experiments.ipynb
    ```

## Folder and files

- `notebooks/`: Jupyter notebooks for different experiments.
    - `synthetic_experiments.ipynb`: experiments using synthetic graphs and data
    - `utils.ipynb`: definitions for useful supporting functions

