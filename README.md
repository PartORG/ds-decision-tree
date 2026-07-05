# Decision Trees

In this repository, we explore the powerful Machine Learning algorithm called Decision Tree using Python. This project is designed to help you understand how to implement and utilize Decision Trees for both regression and classification tasks.

## The Way to Success:

Please work together as **Pair-Programmers** through all the notebooks in this particular order:

1. [Decision Trees Regression](1_Decision_Trees_Visualization.ipynb)
2. [Decision Trees Classification](2_Decision_Trees_Classification.ipynb)
3. [Decision Trees Recap](3_Decision_Trees_Recap.ipynb)

The first notebook will show you how to implement Decision Trees on a regression problem with scikit-learn. In the second notebook, you will use the algorithm on a classification problem. The third notebook recapitulates everything you have learned so far about Decision Trees and provides additional insights from a blog post.

## Objectives

At the end of the notebooks, you should:

- Know how to implement Decision Trees (both classifier and regressor trees) with scikit-learn.
- Know how to plot Decision Trees.
- Understand different splitting criteria for Decision Trees (Gini and Entropy) and how splitting decisions are made while growing the tree.
- Be able to briefly explain the Decision Tree Algorithm to a colleague.
- Know about the advantages and disadvantages of Decision Trees.
- Understand typical terminology (node, stump, leaf, threshold).
- Recap how to write and document functions (regarding length and using doc strings).
- Recap the different steps during a Machine Learning project.

## Installation

Please make sure you have forked the repo and set up a new virtual environment. For this purpose, you can use the following commands:

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the Decision Trees notebooks.

### **`macOS`** type the following commands :

- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```
     **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

    ```Bash
    python.exe -m pip install --upgrade pip
    ```

## Data

The dataset for the notebook is stored in the `data.zip` folder. To unzip the data folder directly in the terminal, run:

```sh
unzip data.zip
```

## Requirements

| Technology | Purpose |
|------------|---------|
| Jupyter Notebook | Interactive environment for running Python code and visualizing results. |
| Matplotlib | For creating static, animated, and interactive visualizations in Python. |
| Seaborn | Based on matplotlib, it provides a high-level interface for drawing attractive statistical graphics. |
| NumPy | Fundamental package for scientific computing with Python. |
| Pandas | Provides data structures and operations for manipulating numerical tables and time series. |
| scikit-learn | Simple and efficient tools for predictive data analysis built on NumPy, SciPy, and matplotlib. |

## Quick Start

1. Fork the repository.
2. Set up a virtual environment as described in the "Installation" section.
3. Unzip the `data.zip` file.
4. Open the notebooks in Jupyter Notebook.

## Usage

To run the notebooks, simply open them in Jupyter Notebook and execute the cells sequentially.

## Project Structure

```
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

Pair-programming is required to work through the notebooks in a specific order. The first notebook covers regression, the second classification, and the third recapitulates learning with additional insights from a blog post.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.