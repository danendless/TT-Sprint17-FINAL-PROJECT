# TT-Sprint17-FINAL-PROJECT

## Setup for Development (recommended)

### 1) Create and activate a project environment using conda based on environment.yaml

    conda env create -n <ENV_NAME> -f environment.yaml
    conda activate <ENV_NAME>

### 2) Access and run the project in this order:
    ./notebooks/01_steelproof_notebook_work_plan.ipynb
    ./notebooks/02_steelproof_notebook_code.ipynb
    ./notebooks/03_steelproof_notebook_report.ipynb

### 3) VS Code

- Open the folder in VS Code (WSL)
- Open the desired notebook and select the kernel that matches <ENV_NAME> (install ipykernel in the env if needed, but it is included in environment.yaml)

Note:
`python -m ipykernel install ...` is generally only needed for standalone Jupyter (browser Jupyter Notebook/Lab), not VS Code.

