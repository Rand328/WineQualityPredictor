# WineQualityPredictor

Dit project voorspelt de kwaliteit van witte wijn op basis van verschillende fysieke en chemische eigenschappen met behulp van machine learning-modellen.

## Projectstructuur

- **Data-analyse**
- **Data Voorbereiding**
- **Model 1 - HistGradientBoostingRegressor**:
  - Een Gradient Boosting-model wordt getraind en geoptimaliseerd met GridSearchCV.
  - Evaluatie met Mean Squared Error (MSE) en R²-score.
- **Model 2 - RandomForestRegressor**:
  - Een Random Forest-model wordt getraind en geoptimaliseerd.
  - Evaluatie met MSE en R²-score.
- **Overfitting/Underfitting Analyse**
- **Ensemble Methodes**:
  - Implementatie van een Voting Regressor en een Stacking Regressor om de modellen te combineren.
  - Evaluatie met cross-validatie.
- **Fine-Tuning**

## Vereisten

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Code Uitvoeren

Voer de code uit in een Jupyter-notebook of Python-omgeving. De code laadt de dataset, traint de modellen, optimaliseert hyperparameters en toont evaluatiemetrieken samen met leercurven.
