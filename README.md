# heart-disease-prediction

This repository contains code and data for analyzing and predicting heart disease using machine learning techniques. The main analysis is performed in a Jupyter notebook (`heart-disease.ipynb`), which includes:

- Exploratory Data Analysis (EDA) of heart disease datasets (`HeartAssign2.csv` and `HeartNewPatients.csv`)
- Data preprocessing and feature engineering
- Visualization of key features and correlations
- Application of machine learning models (such as Random Forest) to predict the presence of heart disease
- Evaluation of model performance

The project uses Python libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn. The datasets contain anonymized patient information with features like age, sex, chest pain type, blood pressure, cholesterol, and more, along with a target variable indicating heart disease presence.

## Files

- `heart-disease.ipynb`: Main Jupyter notebook with code and analysis
- `HeartAssign2.csv`: Primary dataset for training and analysis
- `HeartNewPatients.csv`: Additional dataset for testing or prediction
- `README.md`: This file

## Usage

1. Open `heart-disease.ipynb` in Jupyter or Google Colab.
2. Ensure the CSV data files are present in the same directory.
3. Run the notebook cells to reproduce the analysis and predictions.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

Install dependencies with:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn