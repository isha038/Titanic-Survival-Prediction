
# Titanic Survival Prediction

This project predicts the survival of Titanic passengers using various machine learning models and explores the impact of data preprocessing and feature importance analysis on model performance.

## Project Overview

The Titanic Survival Prediction project demonstrates the end-to-end workflow of a machine learning project, including data preprocessing, feature engineering, model training, evaluation, and feature importance analysis. It leverages XGBoost and other classifiers to achieve robust predictions and interpretability.

## Features

- Preprocessed the Titanic dataset:
  - Handled missing values in features such as `Age`, `Embarked`, and `Fare`.
  - Encoded categorical variables (`Sex` and `Embarked`) into numeric representations.
- Implemented and compared multiple classifiers:
  - XGBoost (with feature importance analysis)
  - K-Nearest Neighbors (KNN)
  - Support Vector Machines (linear and RBF kernels)
  - Random Forests, AdaBoost, and Gaussian Naive Bayes
- Conducted feature importance analysis using XGBoost to identify key predictors of survival.
- Evaluated models using metrics like accuracy and ROC-AUC to assess performance.

## Workflow

1. **Data Preprocessing**:
   - Addressed missing values and encoded categorical features for machine learning compatibility.
   - Explored the impact of preprocessing pipelines on model accuracy.

2. **Model Implementation**:
   - Trained and tested various classifiers, including XGBoost, KNN, SVM, and Random Forest.
   - Conducted feature importance analysis using XGBoost to uncover influential predictors.

3. **Evaluation**:
   - Compared classifiers using accuracy and ROC-AUC metrics.
   - Documented performance trade-offs and interpretability of models.



## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks:
   - Open `titanicSurvivalPrediction_SE.ipynb` to follow the model-building and evaluation process.
   - Open `xgboost.ipynb` to explore feature importance analysis using XGBoost.

## Future Work

- Further refine preprocessing pipelines and normalization techniques to improve model performance.
- Explore advanced ensemble methods such as LightGBM and CatBoost.
- Automate hyperparameter optimization using Grid Search or Bayesian Optimization.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Mississippi State University Data Wrangling Lab(DSCI 2012)

