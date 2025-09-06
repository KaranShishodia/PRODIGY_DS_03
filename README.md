# PRODIGY_DS_03
This project uses a decision tree classifier to predict whether a customer will purchase a product or service. The model is built using Python, leveraging the Scikit-learn library, and trained on the Bank Marketing dataset. The goal is to demonstrate a complete machine learning workflow from data preprocessing to model evaluation and visualization.

# Decision Tree Classifier — Bank Marketing

## Project overview
Build and evaluate a Decision Tree classifier to predict whether a customer will subscribe to a bank product.  
This repo contains a ready-to-run script and a Jupyter notebook for exploratory analysis, model training, evaluation, and visualization.  
The model uses scikit-learn and common preprocessing for categorical variables.

## Dataset
This repository already includes a small built-in sample dataset (`data/bank_marketing.csv`) with a few rows so you can run the project immediately without downloading external data.

For full experiments, you can replace it with the dataset from Prodigy-InfoTech Task 3 (Bank Marketing style).  
Save the dataset as `data/bank_marketing.csv`.

Original reference: [Bank Marketing Dataset](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203)

## Repository structure
decision-tree-bank-marketing/
├─ data/
│ └─ bank_marketing.csv # sample dataset included
├─ notebooks/
│ └─ 01-exploration-and-model.ipynb
├─ src/
│ └─ train_decision_tree.py
├─ outputs/
│ ├─ confusion_matrix.png
│ ├─ decision_tree.png
│ └─ feature_importance.png
├─ requirements.txt
├─ README.md
└─ LICENSE


## How to run (local)
Clone the repo and enter the folder:
```bash
git clone <your-repo-url>
cd decision-tree-bank-marketing

## Create a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
