# Crop Yield Prediction using Machine Learning

## Project Overview
This project predicts crop yield using machine learning techniques based on agricultural production and cultivation cost data. The project demonstrates the complete machine learning workflow, including data understanding, data cleaning, exploratory data analysis (EDA), model training, evaluation, and model saving.

## Objectives
- Analyze agricultural datasets.
- Clean and preprocess the data.
- Perform exploratory data analysis.
- Train machine learning models.
- Compare model performance.
- Predict crop yield.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-learn

## Project Structure

```
Project-4-Crop-Production/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   └── crop_yield_prediction_model.pkl
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_model_training.ipynb
│   └── 05_model_evaluation.ipynb
│
├── outputs/
├── requirements.txt
└── README.md
```

## Machine Learning Models
- Linear Regression
- Decision Tree Regressor

## Model Performance

| Model | R² Score |
|-------|-----------|
| Linear Regression | 0.78 |
| Decision Tree | 0.64 |

Linear Regression achieved the best overall performance and was selected as the final model.

## Future Improvements
- Train using larger datasets.
- Add more agricultural features.
- Deploy the model as a web application.

## Author
**Fardeen Akmal**