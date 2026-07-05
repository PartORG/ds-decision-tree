# Decision Trees for Machine Learning in Python

In this repository, we explore the implementation and application of Decision Trees in Python using scikit-learn.

## Requirements

To run this project, you need the following dependencies with their specified versions:

- `jupyterlab==3.6.3`
- `matplotlib==3.7.1`
- `seaborn==0.12.2`
- `numpy==1.24.3`
- `pandas==2.0.1`
- `scikit-learn==1.2.2`

## Installation

### macOS

To set up your environment on macOS, follow these steps:

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### WindowsOS

For WindowsOS, use the following commands in either PowerShell or Git-Bash:

**PowerShell:**

```powershell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Git-Bash:**

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

If you encounter an error during environment setup, try removing the versions from the failing packages in the `requirements.txt` file.

## Usage

To run the project, follow these steps:

1. Unzip the data folder directly in the terminal:
   ```sh
   unzip data.zip
   ```

2. Open the Jupyter Notebook files in the correct order:
   - [Decision Trees Regression](1_Decision_Trees_Visualization.ipynb)
   - [Decision Trees Classification](2_Decision_Trees_Classification.ipynb)
   - [Decision Trees Recap](3_Decision_Trees_Recap.ipynb)

Each notebook will guide you through implementing Decision Trees on regression and classification problems, plotting them, and understanding their terminology and advantages/disadvantages.