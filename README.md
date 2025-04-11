# Explainable AI on Heart Disease Data

This project explores the use of machine learning and model interpretability techniques to predict the presence of heart disease using clinical data from the UCI repository.

## Features
- Tabular classification using XGBoost and Random Forest
- SHAP-based model interpretability (global and local)
- Clean modular structure with notebooks and scripts
- Ready for deployment via Streamlit (optional)

## Dataset
- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Clean CSV version** used: [here](https://raw.githubusercontent.com/ageron/handson-ml/master/datasets/heart/heart.csv)

## Project Structure

explainable-ml-health/
├── data/               # CSV dataset and processed versions
│   └── heart.csv
├── notebooks/          # Jupyter notebooks for exploration & modeling
│   └── 01_load_and_explore.ipynb
├── src/                # Modular Python scripts
│   ├── preprocessing.py
│   ├── train_model.py
│   └── interpret_model.py
├── results/            # Output plots, metrics, SHAP values
│   └── plots/
├── requirements.txt    # Python package dependencies
├── README.md           # Project documentation
└── .gitignore          # Files to ignore in version control


## Getting Started

1. Clone the repo:

git clone https://github.com/jamesobaldwin/explainable-ai-health.git cd explainable-ai-health


2. Install dependencies:

pip install -r requirements.txt


3. Run the notebooks:

- Start with `notebooks/01_load_and_explore.ipynb`

4. (Optional) Launch the Streamlit dashboard:

streamlit run app.py


## Preview

![SHAP Summary](results/plots/shap_summary.png)




