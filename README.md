#  Sales Forecasting with Linear Regression

A machine learning project that predicts sales based on key business features using Linear Regression, Ridge, and Lasso models.

## Project Structure
sales-forecasting/
├── data/               # Dataset
├── notebooks/          # EDA + Modeling notebooks
├── src/                # Reusable Python scripts
├── models/             # Saved model files
├── requirements.txt    # Dependencies
└── README.md

##  Features Used
- Advertising Spend
- Discount Percentage
- Number of Salespeople
- Competitor Price
- Holiday Flag

##Model Performance
| Model | MAE | RMSE | R² |
|-------|-----|------|----|
| Linear Regression | 1763 | 2200 | 0.9447 |
| Ridge | 1764 | 2200 | 0.9447 |
| Lasso | 1763 | 2200 | 0.9447 |

## How to Run
pip install -r requirements.txt
python setup_project.py
python src/train.py
python src/predict.py

## Tech Stack
- Python
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook
