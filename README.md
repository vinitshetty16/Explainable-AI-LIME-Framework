# Explainable AI with LIME Framework: Predicting Census Income

<img src="https://github.com/vinitshetty16/Explainable-AI-LIME-Framework/assets/63487624/ae1a708f-3f55-4e82-9456-76f0dadd7c0d" alt="image" width="800">

Welcome to your assignment this week! In this assignment, we explore the LIME framework to explain potential black-box machine learning models in a model-agnostic way. Using a real-world dataset on Census income, also known as the Adult dataset available in the UCI ML Repository, we predict if the potential income of people is more than $50K/year or not.
You can view the dataset [here](https://archive.ics.uci.edu/dataset/20/census+income).

## Methodology

We utilize the following methodologies and techniques:

- **XGBoost**: An optimized distributed gradient boosting library used for regression and classification problems.
- **Decision Tree**: A decision support tool used for decision analysis and machine learning.

## Dependencies

- NumPy
- matplotlib
- seaborn
- lime
- shap
- xgboost
- sci-kit-learn

## Conclusion

- We successfully employed the LIME framework to explain predictions made by black-box machine learning models.
- The analysis revealed insights into feature importance, model performance, and decision-making processes.
- Further exploration could involve the use of other interpretation methods and advanced machine learning models for enhanced prediction explanations.

## Results and Insights

- The XGBoost model demonstrated strong performance in predicting Census income, with notable feature importance observed for Age, Education Num, and Hours Per Week.
- Decision Tree analysis revealed a bias towards predicting income below $50K, highlighting potential areas for model improvement.
- LIME explanations provided valuable insights into individual predictions, allowing for a better understanding of model decisions.

## Usage

1. Clone this repository.
2. Install the required dependencies.
3. Run the provided scripts or notebooks to replicate the analysis and results.
4. Explore the generated visualizations and explanations to gain insights into model predictions.
