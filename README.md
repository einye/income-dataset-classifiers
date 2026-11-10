# Adult Income Classification (Census Data)

A complete machine learning classification project using the classic [**Adult Census Income**](https://archive.ics.uci.edu/dataset/2/adult) dataset. The goal is to predict whether a person's annual income exceeds **$50K** based on 14 demographic and employment attributes.

This project explores the full ML pipeline, from raw data exploration and feature engineering to model training and in-depth metric comparison across four classifiers.

## Requirements

- **Python 3.8+**
- Jupyter Notebook / JupyterLab
- [The dataset](https://archive.ics.uci.edu/dataset/2/adult) 

## Note

- If you want to move this to a py file you may need to refactor the `main()` function. Jupyter Notebooks share state, the `for algo, name in models.items():` loop (last cell) depends on X_train, y_train, etc., being globally defined. That's fine for a notebook, but if you want to move this to a .py file, you'll probably need to pass those as arguments, please check for yourself. 

## Installation

```bash
# Clone the repo
git clone https://github.com/einye/income-dataset-classifiers.git
cd income-dataset-classifiers

# (Recommended) Create a virtual environment
python3.12 -m venv venv         #Created on Python 3.12
source venv/bin/activate        # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```
## Acknowledgements

UCI Machine Learning Repository - for the [Adult dataset](https://archive.ics.uci.edu/dataset/2/adult) (originally from the 1994 Census Bureau database).