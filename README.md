# Insurance Cost Prediction Using Machine Learning

A machine learning project that predicts annual medical insurance charges based on personal and health-related factors. The project includes exploratory data analysis, data preprocessing, model training, performance evaluation, and an interactive Streamlit web application.

## Project Overview

The goal of this project is to explore the factors associated with medical insurance costs and build regression models to estimate annual insurance charges.

Users can enter information such as age, BMI, number of children, smoking status, sex, and region to receive an estimated insurance cost.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Streamlit
- Joblib
- Jupyter Notebook

## Machine Learning Workflow

1. **Data exploration:** Examine the insurance dataset and visualize important variables.
2. **Data preprocessing:** Encode categorical variables, explore outliers, and transform insurance charges using a logarithmic transformation.
3. **Model training:** Train Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor models.
4. **Model evaluation:** Compare models using R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
5. **Model selection:** Select the model with the highest test-set R² score.
6. **Web application:** Build an interactive prediction interface using Streamlit.

## Application Features

- Interactive controls for age, BMI, and number of children
- Selection of smoking status, sex, and region
- Estimated annual insurance charges
- Comparison chart showing predicted charges alongside reference averages
- Machine learning predictions using a saved trained model

## Project Files

| File | Description |
|---|---|
| `Project.ipynb` | Data exploration, preprocessing, training, and evaluation |
| `app.py` | Streamlit application |
| `medical_insurance.csv` | Insurance dataset |
| `insurance_model.pkl` | Saved trained machine learning model |
| `model_features.pkl` | Feature names used during training |
| `model_name.pkl` | Selected model name |
| `requirements.txt` | Python dependencies |

## Run Locally

Clone the repository, navigate into the project directory, install the dependencies, and start Streamlit.

```bash
git clone YOUR_REPOSITORY_URL
cd insurance-cost-prediction
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

Open the local URL provided by Streamlit, usually `http://localhost:8501`.

## Limitations

Predictions are estimates based on the dataset and trained models. They are not actual insurance quotations and should not be used as a substitute for professional insurance or medical advice.

## Future Improvements

- Improve model evaluation with cross-validation
- Compare additional regression algorithms
- Add feature importance visualizations
- Expand the application with more interactive data visualizations
- Improve model reproducibility

## Author

Elvira Maloku

Data Science & Machine Learning Project