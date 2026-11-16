# 🏀 NBA Shot Selection and Shot Prediction

## Project Overview
An end-to-end Machine Learning project that analyses historical NBA basketball shooting data of Kobe Bryant and predicts whether a shot will be successful or unsuccessful.

The project applies Exploratory Data Analysis, Statistical Analysis, Feature Engineering, Supervised Machine Learning, and Explainable AI to understand shooting patterns and predict shot outcomes.

## Objectives
- Analyse historical NBA shooting performance.
- Identify important factors influencing shot outcomes.
- Explore shooting efficiency across court zones and shot types.
- Develop machine learning classification models.
- Predict shot success probabilities.
- Evaluate model performance using multiple metrics.
- Generate insights for basketball performance analysis.

## Dataset
- Total records: 30,697
- Features: 25
- Labelled records: 25,697
- Unlabelled records: 5,000
- Target variable: `shot_made_flag`

Target:
- `1` – Shot Made
- `0` – Shot Missed

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib, Seaborn and Plotly
- Scikit-learn
- XGBoost, LightGBM and CatBoost
- SHAP
- Optuna
- MLflow
- FastAPI
- Streamlit
- Joblib

## Machine Learning Algorithms
1. Logistic Regression
2. Random Forest
3. Extra Trees
4. HistGradientBoosting
5. XGBoost
6. LightGBM
7. CatBoost

Ensemble techniques: Soft Voting and Stacking.

## Model Performance

Selected Model: HistGradientBoosting

| Metric | Result |
|---|---:|
| Accuracy | 61.39% |
| F1-score | 60.21% |
| ROC-AUC | 0.6947 |
| Log-loss | 0.6176 |
| Brier Score | 0.2146 |

Evaluation was performed using a chronological hold-out dataset.

## Key Findings
- Restricted Area shots achieved a 61.8% field-goal percentage.
- Two-point shots showed higher shooting efficiency than three-point shots.
- Shot distance and action type were important predictive features.
- SHAP was used to interpret model predictions.
- Drift analysis was performed to identify changes in data distributions.

## Project Structure
- `notebooks/` – Jupyter Notebook and complete analysis.
- `reports/` – Project documentation.
- `outputs/` – Prediction outputs.
- `models/` – Trained machine learning models.
- `src/` – Prediction service, API and dashboard source code.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/nba-shot-selection-prediction.git
```

2. Navigate into the project:

```bash
cd nba-shot-selection-prediction
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the notebook inside the `notebooks` folder and execute the cells in sequence.

## Future Improvements
- Integrate player-tracking data.
- Include defensive pressure and shot-clock information.
- Extend analysis to multiple NBA players.
- Improve prediction performance.
- Deploy an interactive prediction application.

## Conclusion
This project demonstrates the application of Python, Data Analytics, Machine Learning, and Explainable AI to a real-world sports analytics problem.

It provides an end-to-end workflow covering data preprocessing, analysis, model development, evaluation, and prediction.

**Domain:** Sports Analytics | Machine Learning
