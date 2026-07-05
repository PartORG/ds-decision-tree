# Decision Trees: A Comprehensive Guide in Python

[![GitHub Workflow Status](https://github.com/PartORG/ds-decision-tree/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/PartORG/ds-decision-tree/actions/workflows/workflow-02.yml)
[![Language](https://img.shields.io/github/languages/top/PartORG/ds-decision-tree?color=blue)](https://github.com/PartORG/ds-decision-tree)
[![License](https://img.shields.io/github/license/PartORG/ds-decision-tree?color=green)](https://github.com/PartORG/ds-decision-tree/blob/main/LICENSE)

## Introduction

Welcome to the Decision Trees repository! This project is designed to help you understand and implement Decision Tree algorithms in Python using scikit-learn. Whether you're a beginner or an experienced data scientist, this guide will provide you with a solid foundation in decision tree concepts and practical implementation.

### What It Does
This repository contains three Jupyter notebooks that cover the basics of decision trees:
1. **Decision Trees Regression**: Learn how to implement decision trees for regression problems.
2. **Decision Trees Classification**: Apply decision trees to classification tasks.
3. **Decision Trees Recap**: Summarize key concepts and provide a deeper dive into decision tree algorithms.

### Why It Exists
The primary goal of this project is to make decision trees accessible and understandable through practical examples. By working through these notebooks, you'll gain hands-on experience with decision trees and develop a strong foundation in machine learning.

### Who Is It For?
This guide is ideal for:
- Data scientists looking to deepen their understanding of decision trees.
- Machine learning enthusiasts who want to implement decision trees in Python.
- Students studying data science or machine learning.

### What Problem Does It Solve?
Decision Trees are widely used in various applications, including:
- Predictive analytics
- Fraud detection
- Customer segmentation
- Risk assessment

This repository provides a step-by-step approach to implementing and understanding decision trees, making it easier for anyone to apply these techniques in real-world scenarios.

## How It Works

### Architecture Overview
The project consists of three Jupyter notebooks that follow a sequential learning path:
1. **Decision Trees Regression**: Focuses on regression problems.
2. **Decision Trees Classification**: Covers classification tasks.
3. **Decision Trees Recap**: Summarizes key concepts and provides additional insights.

Each notebook includes practical examples, code snippets, and explanations to help you understand the underlying concepts.

### Technology Stack
| Technology | Purpose |
|------------|---------|
| Jupyter Notebook | Interactive environment for data analysis and visualization. |
| scikit-learn | Machine learning library in Python. |
| matplotlib & seaborn | Libraries for data visualization. |
| numpy & pandas | Libraries for numerical and data manipulation. |

## Requirements

To run the notebooks, you need to have Python installed on your system. The required packages are listed in the `requirements.txt` file.

### Installation

#### macOS
```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

#### WindowsOS (PowerShell)
```powershell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

#### WindowsOS (Git-Bash)
```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

If you encounter an error during environment setup, try removing the versions from the failing packages in the `requirements.txt` file.

## Configuration

No specific configuration is required for this project. Ensure that your virtual environment is activated before running the notebooks.

## Quick Start

1. Fork and clone the repository.
2. Set up a new virtual environment as described above.
3. Activate the virtual environment.
4. Install the required packages using `pip install -r requirements.txt`.
5. Unzip the data folder by running `unzip data.zip`.
6. Open the Jupyter notebooks in sequence (`1_Decision_Trees_Visualization.ipynb`, `2_Decision_Trees_Classification.ipynb`, and `3_Decision_Trees_Recap.ipynb`).

## Usage

Each notebook provides detailed instructions on how to implement decision trees for regression and classification tasks. Key concepts such as splitting criteria (Gini and Entropy), node terminology, and function documentation are covered.

### Example Commands
```python
# Import necessary libraries
import pandas as pd
from sklearn.tree import DecisionTreeRegressor
from sklearn.model_selection import train_test_split

# Load data
data = pd.read_csv('data.csv')

# Split data into features and target
X = data.drop('target', axis=1)
y = data['target']

# Split data into training and testing sets
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Create a decision tree regressor
model = DecisionTreeRegressor()

# Train the model
model.fit(X_train, y_train)

# Make predictions
predictions = model.predict(X_test)
```

## Project Structure

```plaintext
ds-decision-tree/
├── .github/workflows/
│   ├── REGX_test_import_libraries.sh
│   ├── add_issue_to_done.yml
│   ├── add_issues_in_todo.yml
│   ├── add_pr_in_progress.yml
│   ├── add_pr_to_done.yml
│   ├── discord-webhook-notify.yml
│   ├── replacement.yml
│   └── workflow-02.yml
├── .gitignore
├── 1_Decision_Trees_Visualization.ipynb
├── 2_Decision_Trees_Classification.ipynb
├── 3_Decision_Trees_Recap.ipynb
├── Decision_Tree.svg
├── Decision_Tree_Recap.excalidraw
├── LLCP_2022_Codebook_Report.pdf
├── README.md
├── data.zip
└── helper_and_plotting_functions.py
```

## Development

This project is open-source and welcomes contributions. If you find any issues or have suggestions for improvements, please feel free to submit a pull request.

## Testing

No tests are currently available for this project.

## Limitations

- The repository assumes basic knowledge of Python and machine learning concepts.
- No advanced optimization techniques are covered in the notebooks.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using the Decision Trees repository! If you have any questions or need further assistance, feel free to reach out.