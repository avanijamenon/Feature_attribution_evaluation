# Titanic Survival Prediction with Explainable AI
This project investigates a neural network approach for predicting Titanic passenger survival and employs various Explainable AI (XAI) techniques to interpret model decisions. Exploratory data analysis reveals that passenger class (Pclass) and gender (Sex) are the strongest predictors of survival, with Fare acting as a proxy for socioeconomic status. Feature-attribution methods including SHAP, SVS, and DeepLIFT consistently identify these same factors as the most influential. Counterfactual explanations (NNCE and WAC) demonstrate minimal changes required to switch predictions, with NNCE relying on real data points for increased plausibility and WAC generating synthetic but lower-cost scenarios. These findings highlight the synergy between neural network models and XAI methods in providing both predictive accuracy and transparent insights into survival outcomes.

This repository includes:

- Data Preprocessing scripts for cleaning and encoding passenger information.
- Model Training notebooks for building and evaluating the neural network classifier.
- Explainable AI modules demonstrating SHAP, SVS, and DeepLIFT feature attributions.
- Counterfactual Explanations implementations of NNCE and WAC for generating alternative “what-if” scenarios.
